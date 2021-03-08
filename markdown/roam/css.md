- [[Conor]]
    - Spacer 
        - ```css
 
.rm-block__self  .rm-block-separator {
  min-width: 100px ;
  min-height: 10px;
  background-color: #4CAF50;
  flex: 1 0 100px;
}

.rm-block__self > .rm-block-separator {
  min-width: 100px;
/  min-height: 10px;
  background-color: #4CAF50;
  flex: 1 0 100px;
}

.rm-embed-container  .rm-embed-inner-block-hide  
.rm-block > .rm-block__self > .rm-block-separator {
  min-width: 0px;
  min-height: 10px;
  background-color: blue;
}
```
    - New Document Mode
        - 
            - ```css
.doc-mode  .rm-block__self:not(:hover)  .rm-block__controls {
opacity: 0.1;
}


.path-highlighted {
  opacity: 1 !important;
 
}

.doc-mode :not(.rm-block--open) > .rm-block__children {
  margin-left: 0px;
}

.doc-mode .rm-block--open :not(.rm-heading-level-1,.rm-heading-level-2,.rm-heading-level-3) .rm-block__children:not(:hover) .rm-multibar {
  opacity: 0;
}



.doc-mode .rm-block--open > .rm-block__children > .rm-block 
.rm-block__controls {
opacity: 1 !important;
 
}

.doc-mode :not(.rm-heading-level-1,.rm-heading-level-2,.rm-heading-level-3) 
.rm-block__children
.rm-block__self:not(:hover)
.rm-block__controls {
  opacity: 0 !important;
}

.doc-mode .rm-block--open :not(.rm-heading-level-1,.rm-heading-level-2,.rm-heading-level-3,.rm-heading-level-4) > .rm-block__children {
  margin-left: 16px;
}

.doc-mode  .rm-block__children {

  margin-left: 0px;
 
}
/*

.rm-heading-level-1:hover > .rm-block__children {
  background-color: rgba(211,211,211,0.11);
  border-top: 1px solid grey;
  margin-left: 8px;
}

.rm-heading-level-2:hover > .rm-block__children {
  background-color: rgba(211,211,211,0.11);
  border-top: 1px solid grey;
  margin-left: 8px;
}

.rm-heading-level-3:hover > .rm-block__children {
  background-color: rgba(211,211,211,0.11);
  border-top: 1px solid grey;
  margin-left: 8px;
}
*/
```
                - ```css

.doc-mode > .rm-block__children:not(.rm-heading-level-1)  .rm-multibar {
  border-color: transparent;
}

```
    - Test Table
        - ```css
.conor-table .rm-block__children {
  display: contents;
  
}

.conor-table > .rm-block__children .rm-block {
  display: grid;
  grid-template-columns: repeat(6, 100px);
  grid-template-rows: 40px;
}

.conor-table {
  border: 2px solid grey;
  width: 50vw;
}

.conor-table .rm-block {
  border: 0.5px solid grey;
flex: 1 1 60px;
}

.conor-table  .a > .rm-block__self {
  background-color: blue;
  opacity: 0.4;
  color: white;
}```
    - ```css
.test-full-width {	
  position: fixed;
  left: 0px;
  right: 100px;
  bottom: 0px;
  z-index: -1;
  opacity: 0.4;
}```
    - ```css
.mindmap {
  overflow: scroll;
background-color: rgba(211,211,211,0.31);
 min-width: 70vw;
  
  margin: 0px !important;
  padding: 8px !important;
}

.mindmap > .rm-block__children {
  min-width: 100%;
}

.mindmap .rm-block__children .rm-block {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.mindmap .rm-block__children .rm-block__input {
  border-left: 1px solid grey;
  border-top: 1px solid grey;
  border-bottom: 1px solid grey;
  padding: 8px;
}
.mindmap .rm-block__children .rm-block__self {
  flex-grow: 0.1;
}
.mindmap .rm-block__children .rm-block__children .rm-block__controls {
opacity: 1;
  position: relative;
  align-self: center;
}

.mindmap .rm-block__children .rm-block__children .block-expand  {
  opacity: 1;
  background-color: green;
  height: 4px;
  align-self: center;
  min-width: 80%;
  margin-left: -4px;
  position: relative;
}

.mindmap .rm-block__children .rm-block__children .block-expand span {
  opacity: 1;
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background-color: green;
  color: transparent;
  transform: none !important;
}

.mindmap .rm-block__children .rm-block__children {
   flex-grow: 1;
  margin: 12px 4px;
  padding: 8px 0px;
 
}

```
        - ```css

.mindmap .rm-block__children .rm-block__children .rm-multibar {
  opacity: 1;
  top: 1em;
  bottom: 1em;
  background-color: green;
  width: 4px;
}```
    - ```css
.group {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.group div {
  border: none;
}
.group > .rm-block__self {
  flex-grow: 0.1;
}
.group .rm-block__children .rm-block__controls {
opacity: 0;
}
.group:hover .rm-block__children .rm-block__controls {
opacity: 1;
}

.group > .rm-block__children {
   flex-grow: 1;
  margin: 12px 4px;
  padding: 8px 0px;
  border-top: 1px solid green;
  border-bottom: 1px solid green;
  border-left: 1px solid green;
}```
    - ```css
.grey-hl .rm-highlight {
  background-color: transparent;
  color: gray;
}
```
    - ```css
.big .rm-highlight {
  background-color: transparent;
  font-size: 2em;
}```
    - ```css
.Falsified {
text-decoration: line-through;
}```
    - Old Block level styling
        - ```css
.roam-block-container[data-page-links*="horizontal"] 
.rm-block-children {
  display: flex;
  flex-direction: row;
 
}
.roam-block-container[data-page-links*="horizontal"] 
 .rm-block__controls {
  display: none;
 
}```
        - Hide the tag
            - ```css
span.rm-page-ref[data-tag="rm-h"] {
    display: none;
}

.roam-block-container[data-page-links*="rm-h"] .rm-block-children {
  display: flex;
  flex-direction: row;
}
```
        - Grid #rm-grid
            - Grid 1
            - Grid 2
            - Gr
        - Grid `#rm-grid`
            - ```css

.roam-block-container[data-page-links*="rm-grid"] .rm-block-children {
  display: grid;
  background-color: #F7F8F8;
  
 grid-template-columns: repeat( auto-fit, minmax(150px, 1fr) );
}```
        - Blue border for children
            - ```css
.rm-block[data-path-page-links*="rm-blue-border--children"]{
  border: 1px solid blue;
}```
        - Span 2 columns
            - ```css
.roam-block-container[data-page-links*="rm-col-span2"] {
  grid-column: span 2;
}```
        - Span 2 rows 
            - ```css
.roam-block-container[data-page-links*="rm-row-span2"] {
  grid-row: span 2;
}```
        - Hide the `.rm` tags
            - ```css
.roam-block-container[data-page-links*="rm-hide"]
span.rm-page-ref[data-tag*="rm"] 
{
  display: none;
}```
    - New block level styling
        - ```css
.bblue {
  border: 2px solid blue !important;
}```
        - ```css
.green  {
  margin: 2px;
  background-color: green;
  color: white;
}```
    - ```css
.conor-shrink {
  
  transform: scale(0.8);
}```
- #Evergreens
- Live Editor for playing with custom tags {{[[table]]}}
    - ```css

span.rm-page-ref[data-tag="Evergreens"] {
    background: #FF5722 !important;
    color: #fff !important;
    padding: 3px 8px;
    line-height: 2em;
    font-weight: 500;
}
```
        - #Evergreens
    - ```css
span.rm-page-ref[data-tag="Seedling"] {
    color: #4CAF50 !important;
    padding: 3px 3px;
    font-weight: 600;
    line-height: 1.4em;
}
```
        - #Seedling 
    - ```css
span.rm-page-ref[data-tag="Idea Bank"] {
    color: #3C34EA !important;
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"]:before {
    content: '✦ '
}
```
        -  #[[Idea Bank]]
    - ```css
span.rm-page-ref[data-tag="Essay"] {
    background: #03A9F4;
    color: #fff;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}
```
        - #Essay
- Make wide
    - ```css
[data-tag="make:wide"] ~ div {
	width: 110% !important;
}

[data-tag="make:wide-x"] ~ div {
	width: 120% !important;	
}

[data-tag="make:wide-xx"] ~ div {
	width: 130% !important;	
}

[data-tag="make:wide-xxl"] ~ div {
	width: 150% !important;
}


[data-tag="make:wide-on-hover"] ~ div:hover {
  transform: scale(1.5); 
}

[data-tag*="make:wide"] ~ div div:nth-child(2){
	width: 100% !important;
}



[data-tag="make:long"] ~ div {
	height: 660px !important;
}

[data-tag="make:long-x"] ~ div {
	height: 760px !important;
}

[data-tag="make:long-xx"] ~ div {
	height: 860px !important;
}

[data-tag="make:long-xxl"] ~ div {
	height: 960px !important;
}


[data-tag*="make:long"] ~ div div:nth-child(2){
	height: 100% !important;
}```
- Customizing Nested Tables and embeds
    - ```css
/* don't limit the block width for tables */
span.rm-page-ref[data-tag="make:table-tight"] ~ div .rm-block-text {
    max-width: none!important;
}

/* clean up tables embedded in tables and blocks within tables */
span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table, .roam-table th, .roam-table td, .roam-table tr {
    padding:0!important;
    vertical-align: top;
    min-width:auto!important;
    overflow: hidden;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table .roam-table table {
    width:100%;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table .rm-block-ref {
    padding:0!important;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table .rm-embed-container {
    background-color:transparent!important;
    padding-bottom:20px;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table .rm-embed-edit, .roam-table .bp3-popover-wrapper {
    display:none!important;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table .controls .block-expand .rm-caret {
    transition:none!important;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .rm-embed-inner-block-hide:hover {
    margin-left:-42px!important;
}

span.rm-page-ref[data-tag="make:table-tight"] ~ div .roam-table .roam-table th, .roam-table  .roam-table td, .roam-table  .roam-table tr {
    border-bottom:0;
    border-left:0;
    border-top:0;
}

```
