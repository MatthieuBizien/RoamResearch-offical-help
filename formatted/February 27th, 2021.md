- 
- {{iframe: https://roamresearch.com/#/app/roam-depot-developers/page/1Gi7pQS1K}}
- #.conor-shrink 
    - [reference-history](<reference-history.md>) [DONE](<DONE.md>)
- **[[ ] [Choice](<Choice.md>) What should I show bruce first"Decision](<[ ] [Choice](<Choice.md>) What should I show bruce first"Decision.md>):** "The way I use it for [Hammock Driven Development](<Hammock Driven Development.md>)?""
    - **[Options](<Options.md>):**
        - The way I use it for [Hammock Driven Development](<Hammock Driven Development.md>)?
            - **[Advantages](<Advantages.md>):**
                -  It's my main way of working in Roam
            - **[Disadvantages](<Disadvantages.md>):**
                - It isn't how most users use Roam
        - The way you can use it for [Designed](<Designed.md>) [Serendipity](<Serendipity.md>)
    - **[Decision](<Decision.md>):** "The way I use it for [Hammock Driven Development](<Hammock Driven Development.md>)?"
- 
- **TODOs** #.rm-h
    - More customization (date range, color legend range)
    - Support general queries (AND and OR)
    - Write as a roam/render component
- {{[roam/js](<roam/js.md>)}}
    - ```javascript
;(function () { 
function loadLibrary(name, src) {
	const oldLib = document.getElementById(name)
 	if (oldLib) oldLib.remove()
    const s = document.createElement('script')
  	s.src = src
 	s.id = name
  	s.async = false
  	s.type = 'text/javascript'
  	document.getElementsByTagName('head')[0].appendChild(s)
}

function loadCss(src) {
    const l = document.createElement('link')
    l.rel = 'stylesheet'
    l.href = src
    document.getElementsByTagName('head')[0].appendChild(l)
}

function appendToBlock(block, childEl) {
    const div = document.createElement('div')
    div.classList.add('flex-v-box')
    div.appendChild(childEl)
    block.appendChild(div)
}

function isDatePage(name) {
  	if (!name) return false
  	return name.match(/^\w+\s\d\d?..,\s\d\d\d\d$/)
}

function parseDatePage(name) {
  	if (!isDatePage(name)) return null
    const months = [
        'January', 'February', 'March', 'April', 'May', 'June', 'July',
        'August', 'September', 'October', 'November', 'December']
    const dateParts = name.split(' ')
    const month = months.indexOf(dateParts[0])
    const day = parseInt(dateParts[1].substring(0, dateParts[1].length - 2), 10)
    const year = parseInt(dateParts[2], 10)
    return new Date(year, month, day)
}

function getPageName(node) {
  if (node.title) {
    return node.title
  } else if (node._children) {
    return getPageName(node._children[0])
  }
  return null
}

function getPageCalData(pages) {
  const refs = pages.map(page =>
    window.roamAlphaAPI.q(`
		[:find 
			(pull ?block [:node/title {:block/_children ...}]) 
			:where [?block :block/refs ?ref] [?ref :node/title "${page}"]]`))
  	.flat();
    // TODO: parameterize use of indirect refs
    /*const indirectRefs = await window.roamAlphaAPI.q(`
		[:find 
			(pull ?block [:node/title {:block/_children ...}]) 
			:where
				[?source :block/refs ?ref]
				[?ref :node/title "${page}"]
				[?block :block/refs ?source]]`)*/
  	const dates = refs.map(n => getPageName(n[0])).filter(isDatePage).map(parseDatePage)
    if (dates.length == 0) return
    const data = {}
    dates.forEach(d => {
      	const timestamp = Math.floor(d.getTime() / 1000).toString()
        data[timestamp] ||= 0
      	data[timestamp]++
    })
	return data
}

function isBacklinkCalBlock(block) {
    try {
      if (JSON.parse(block.dataset.pageLinks).indexOf('reference-history') >= 0)
        return true
    } catch (err) {}
    return false
}

function addBacklinkCal() {
    [...document.getElementsByClassName('roam-block-container')]
  		.filter(isBacklinkCalBlock).forEach(block => {
      	if (block.dataset.isBacklinkCalDone) return
      	const links = new Set(JSON.parse(block.dataset.pageLinks))
        links.delete('reference-history')
      	const pages = [...links]
        if (pages.length === 0) return
  
        const calEl = document.createElement('div')
        calEl.id = 'cal-heatmap-' + Math.floor(Math.random() * 1000000)
        appendToBlock(block, calEl)
        const cal = new CalHeatMap()
        const start = new Date(new Date().getTime() - 11*30*24*60*60*1000)
        const data = getPageCalData(pages);
        cal.init({data, start,
                  itemSelector: '#' + calEl.id,
                  domain: 'month',
                  subDomain: 'day',
                  legend: [2, 4, 6, 8]});
        block.dataset.isBacklinkCalDone = true
    })
}

loadLibrary('lib-d3', 'https://cdnjs.cloudflare.com/ajax/libs/d3/3.5.6/d3.min.js')
loadLibrary('lib-calheatmap', 'https://cdn.jsdelivr.net/cal-heatmap/3.3.10/cal-heatmap.min.js')
loadCss('https://cdn.jsdelivr.net/cal-heatmap/3.3.10/cal-heatmap.css')
window.setInterval(addBacklinkCal, 1000)
})();```
