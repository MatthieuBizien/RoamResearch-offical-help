- 23:12 - 01:21 (2 hour 10 minutes)
    - 23:12 - 23:52
        - Let's test mindmap via [roam/css](<roam/css.md>)
            - Iteratons
                - Step 1
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FEmJhviA4Hg.png?alt=media&token=3293b5b8-2ec0-47e6-8a3d-31f6ab1b5f19)
                        - Result of 
                            - ```css
.mindmap {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.mindmap .rm-block__input {
  border: 1px solid grey;
}
.mindmap > .rm-block__self {
  flex-grow: 0.1;
}
.mindmap .rm-block__children .rm-block__controls {
opacity: 1;
  position: relative;
}


.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}

.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}

.mindmap > .rm-block__children {
   flex-grow: 1;
  margin: 12px 4px;
  padding: 8px 0px;
  border-top: 1px solid green;
  border-bottom: 1px solid green;
  border-left: 1px solid green;
}``` [*](((WD92x3LBi)))
                - Step 2 [css](((WD92x3LBi)))
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2F23f6pfr2jN.png?alt=media&token=2c02e69e-dcfb-421b-a892-eb2209eabcfa)
                        - **[Result of](<Result of.md>):**
                            - ```javascript

.mindmap .block-expand  {
  opacity: 1;
  background-color: green;
  height: 4px;
  align-self: center;
  min-width: 80%;
  margin-left: -4px;
}```
                                - **[at](<at.md>):** 23:23
                - Step 3
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FFyJHFi6Qtg.png?alt=media&token=bbea05f3-c690-4d2e-af9b-4eb1e28461c3)
                        - **[Result of](<Result of.md>):**
                            - ```css
.mindmap {
  overflow: scroll;
}

.mindmap .rm-block__children .rm-block {
  display: flex;
  align-items: center;
  flex-direction: row;
}
.mindmap .rm-block__children .rm-block__input {
  border: 1px solid grey;
  padding: 8px;
}
.mindmap .rm-block__children .rm-block__self {
  flex-grow: 0.1;
}
.mindmap .rm-block__children .rm-block__children .rm-block__controls {
opacity: 1;
  position: relative;
}


.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}

.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}


.mindmap .rm-block__children .block-expand  {
  opacity: 1;
  background-color: green;
  height: 4px;
  align-self: center;
  min-width: 80%;
  margin-left: -4px;
}

.mindmap .rm-block__children .rm-multibar {
  opacity: 0;
}
.mindmap .rm-block__children .rm-block__children {
   flex-grow: 1;
  margin: 12px 4px;
  padding: 8px 0px;
 
}``` [*](((WD92x3LBi)))
                            - 
                        - 23:34
                - Final Result for now
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2Fqm2mj8zA-d.png?alt=media&token=58fa05d1-6754-4333-85cc-b21b021659df)
                        - **[Result of](<Result of.md>):**
                            -  ```css
.mindmap {
  overflow: scroll;
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
}


.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}

.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}


.mindmap .rm-block__children .rm-block__children .block-expand  {
  opacity: 1;
  background-color: green;
  height: 4px;
  align-self: center;
  min-width: 80%;
  margin-left: -4px;
}

.mindmap .rm-block__children .rm-block__children {
   flex-grow: 1;
  margin: 12px 4px;
  padding: 8px 0px;
 
}``` [*](((WD92x3LBi)))
                - Taken further
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FXhumF0SsBB.png?alt=media&token=130a1fe5-29b5-44da-9da8-6a820a68a166)
                        - **[Result of](<Result of.md>):**
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
}


.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}

.mindmap:hover .rm-block__children .rm-block__controls {
opacity: 1;
}


.mindmap .rm-block__children .rm-block__children .block-expand  {
  opacity: 1;
  background-color: green;
  height: 4px;
  align-self: center;
  min-width: 80%;
  margin-left: -4px;
}

.mindmap .rm-block__children .rm-block__children {
   flex-grow: 1;
  margin: 12px 4px;
  padding: 8px 0px;
 
}``` [*](((WD92x3LBi)))
            - Workspace 
                - test
                    - 
                    - 1
                        - 2 #.mindmap
                            - This is not going to be quite right
                                - A "C"
                                    - C
                                        - D
                                - {{[embed](<embed.md>): ((dr7PdJAjs))}}
                                    - B
                                - In another context {{[embed](<embed.md>): ((tGuGzjThB))}}
                                    - 
                                - X
                                    - C
                                        - "B"
                                            - E
                - Editor
                    - {{[embed](<embed.md>): ((WD92x3LBi))}}
                - #.mindmap
                    - test
                        - X
                            - Y
                            - Z
                                - 
            - Testing with an embedded page or block
            - Video of me writing it
                - {{[video](<video.md>): https://www.loom.com/share/a49deee0d918461ba7c26208056c188c}}
                    - 
                - #.mindmap
                    - {{embed: [How can we develop transformative tools for thought?](<How can we develop transformative tools for thought?.md>)}}
                - #.mindmap
                    - {{[embed](<embed.md>): ((LDz19VdCH))}} 
                - #.mindmap
                    - {{[embed](<embed.md>): [Roam White Paper](<Roam White Paper.md>)}}
                    - {{[embed](<embed.md>): [It's Time To Build](<It's Time To Build.md>)}}
                - 
    - 00:25 - 00:44
        - Thinking about how to use `[.mindmap](<.mindmap.md>)` with real content 
            - [.mindmap](<.mindmap.md>)
                - [Tangent](<Tangent.md>)s
                - Starting Questions
                    - What Needs to Improve
                        - It's way way too hard to make Roam full width 
                            - Particularly as a block level setting
                                - **[Who might I ask for help?](<Who might I ask for help?.md>):**
                                    - #[From](<From.md>) [Roam Team](<Roam Team.md>)
                                        - [Adam](<Adam.md>)
                                    - [From](<From.md>) [RoamCult](<RoamCult.md>)
                                        - Creators of [Roamcult Themes](<Roamcult Themes.md>)
                        - Drawing the line that connects children of a block to their parents
                            - Specific Problems
                                - The height is calculated relative to all nested items - but we really only want it to be positioned 
                                    - **[Who might I ask for help?](<Who might I ask for help?.md>):**
                                        - [Azlen Elza](<Azlen Elza.md>)
                    - Who might I ask for help - Query
                        - {{[query](<query.md>): {and: ((pg17vClzH)) [Who might I ask for help?](<Who might I ask for help?.md>)}}}
                    - All Question tags
                        - {{[query](<query.md>): {and: ((pg17vClzH)) [Question](<Question.md>)}}}
                - [Highest Priority](<Highest Priority.md>) [Problems](<Problems.md>) to Solve
                    - "It's way way too hard to make Roam full width "
                        - This feels especially Aggravating When trying to do more visual stuff
                        - **[Potential Solutions](<Potential Solutions.md>):**
                            - Use CSS Grid top level
                            - Remove the default calculated padding outright
                                - **[Limitations](<Limitations.md>):**
                                    - Will create problems with overlapping sidebar
                                    - "[Tangent](<Tangent.md>)s"
                                        - Noticed that Block Refs here are much nicer than Queries
                                        - Block Embeds are even more counterintuitive than normal though
                            - Move it into a theme
                        - [Question](<Question.md>)
                            - Do I have the original constraints written down for when I initially decided to use that calculated inline style?
        - {{[embed](<embed.md>): ((PZFg4yFBW))}}
        - Uses
            - {{embed: ((WD92x3LBi))}}
    - 00:44 - 00:59 [Tangent](<Tangent.md>) [Ignore](<Ignore.md>)
        - Challenges right now - every block is position relative
            - Ā Ė 
                - test{{[embed](<embed.md>): ((3DXwUyiy0))}}
            - 
                - {{[embed](<embed.md>): [roam/css](<roam/css.md>)}}
                - {{embed: ((V6fuEaI8V))}}
            - #.bp3-card #.full-width
                - 
                - {{[embed](<embed.md>): ((V6fuEaI8V))}}
    - 00:59 - 01:20 (21 minutes)
        - "Iteratons"
            - Final result
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FomlOyY7Wb8.png?alt=media&token=4b322671-f786-43b2-8af6-32921b89d524)
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
 
}``` [*](((WD92x3LBi)))
    - 00:59 - 01:20
- asdfasdf
    - asdfasdf

# Backlinks
## [Roam Change Log](<Roam Change Log.md>)
- [February 21st, 2021](<February 21st, 2021.md>)

