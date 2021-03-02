- [Roam Change Log](<Roam Change Log.md>)
    - Customize display of Roam Blocks based on the links in them, and the links above them.
        - {{[video](<video.md>): https://www.loom.com/embed/06b03473bcda4728b5bef40929e5012f}}
            - # Horizontal Children
                - Testing css customizations [horizontal](<horizontal.md>)
                    - How it works                                     .
                        - Put some code like this in a page called [roam/css](<roam/css.md>)
                        - This will have every set of nested children grouped into columns
                    - "```css
.roam-block-container[data-page-links*="horizontal"] 
.rm-block-children {
  display: flex;
  flex-direction: row;
 
}
.roam-block-container[data-page-links*="horizontal"] 
 .rm-block__controls {
  display: none;
 
}```"
                        - `.roam-block-container[data-page-links*="horizontal"] .rm-block-children {
display: flex;
  flex-direction: row;
}`
            - Now let's hide that tag "Hide the tag" [rm-h](<rm-h.md>) **click and you'll see** `rm-h`
                - A
                - B
                - C
            - # .rm-grid 
                - Let's try a quick grid #.rm-grid "Grid `[rm-grid](<rm-grid.md>)`"
                    - A
                    - B
                    - C
                    - D
                    - E
                    - F
                    - G
                - We can mix the tags up too [rm-blue-border--children](<rm-blue-border--children.md>) [rm-grid](<rm-grid.md>)
                    - a
                    - b
                - And let's make a particular item span two columns
                    -  [rm-grid](<rm-grid.md>) [rm-blue-border--children](<rm-blue-border--children.md>) 
                        - A [rm-col-span2](<rm-col-span2.md>)
                        - B
                        - C
                        - D
                        - F [rm-col-span2](<rm-col-span2.md>)
                        - E
                - And make another that has two rows - while we're at it
                    -   [rm-grid](<rm-grid.md>) [rm-blue-border--children](<rm-blue-border--children.md>) 
                        - A [rm-col-span2](<rm-col-span2.md>)
                        - B
                        - C
                        - D is a larger block of text which will span 2 rows [rm-row-span2](<rm-row-span2.md>)
                        - F [rm-col-span2](<rm-col-span2.md>) [rm-row-span2](<rm-row-span2.md>)
                        - A
                        - B 
                        - E [rm-col-span2](<rm-col-span2.md>)  [rm-row-span2](<rm-row-span2.md>)
                        - C
                        - D
                        - 
                - And as our last trick - let's just make every tag that starts with rm-hidden [rm-hide](<rm-hide.md>)
                    -   [rm-grid](<rm-grid.md>) [rm-blue-border--children](<rm-blue-border--children.md>)  "```css
.roam-block-container[data-page-links*="rm-hide"]
span.rm-page-ref[data-tag*="rm"] 
{
  display: none;
}```"
                        - A [rm-col-span2](<rm-col-span2.md>)
                        - B
                        - C[rm-row-span2](<rm-row-span2.md>)
                        - F [rm-col-span2](<rm-col-span2.md>) "![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2F5UewMaPENW.png?alt=media&token=5f0da069-4d80-442c-9081-207f4c0c8edf)"
                        - D
                        - D is a larger block of text which will span 2 rows [rm-row-span2](<rm-row-span2.md>)
                        - E
                        - A
                        - B 
                        - # This is a Bigger Area  [rm-row-span2](<rm-row-span2.md>)
                        - C
                        - Another
                        - The last one
                        -  [rm-col-span2](<rm-col-span2.md>) Spanning two columns
    - [New Features](<New Features.md>)
        - [Expandable Parentheticals](<Expandable Parentheticals.md>)
            - **[How it works](<How it works.md>):**
                - If you type `((with text inside - but NOT converted into a block reference))` it will now display like this ((((91CCj9YQc)) that's the ((symbol you see here)) ))
                    - thanks to [@Juvoni](<@Juvoni.md>) for showing us the [Unicode [[Astrolabe](<Unicode [[Astrolabe.md>)]] 
                - Clicking on the astrolabe will expand the parenthetical.
                - Clicking on either parenthesis of the open block will close the Parenthetical
                - 
            - **[Limitations](<Limitations.md>):**
                - (([Links](<Links.md>) and )) ((other **formatted**)) text will not parse ((((c3NvrBVHc))))
                    - **[Workaround](<Workaround.md>):**
                        - Block References do parse - so you can extract any rich text into a block and then wrap the block ref in a parenthetical
            - 
            - [Ancestors](<Ancestors.md>) and [inspiration](<inspiration.md>)
                - We're tempted to call this [Telescopic Text](<Telescopic Text.md>) - but the real version of that seems much more impressive
                    - **[The Ones Who Crossed The Rubicon](<The Ones Who Crossed The Rubicon.md>):** 
                        - https://twitter.com/azlenelza/status/1331583299957911554?s=20
                        - https://getcoleman.com/
                        - https://www.telescopictext.org/text/KPx0nlXlKTciC
                        - [Stretch Text](<Stretch Text.md>) from [Ted Nelson](<Ted Nelson.md>)
                            - https://en.wikipedia.org/wiki/StretchText

# Backlinks
## [Roam Change Log](<Roam Change Log.md>)
- [December 14th, 2020](<December 14th, 2020.md>)

