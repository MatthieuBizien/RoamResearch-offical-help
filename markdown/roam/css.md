- #.doc-mode
    - From having a dark theme to opening multiple panels, with a few clicks (and no coding skill required), roam/css helps you customize the look and feel of your Roam graph
    - Check out our [community-built themes for inspiration]([[Themes]])
    - ## Articles::
        - ### [Painting Roam with Custom CSS](https://maggieappleton.com/paintingroam) by [[Maggie Appleton]]
        - ### [Roam themes: how to style Roam Research with custom CSS](https://nesslabs.com/roam-research-themes-custom-styling-css) by [[Anne-Laure Le Cunff]]
    - ## Community Videos::
        - ### How to do color tagging in Roam by [[Zack Fan]]
            - {{[[video]]: https://www.youtube.com/watch?v=kUgAqyzwGzw&t=99s}}
        - ### How to Create and Edit Roam CSS: Interview with [[Abhay Prasanna]] 
            - {{[[video]]: https://www.youtube.com/watch?v=Cz07-oZlPzA&t=3s&ab_channel=MikeGiannulis}}
    - ## Roam Team Videos::
        - ### Applying Custom Themes for your RoamResearch Knowledge Graph by [[Conor White-Sullivan]]
        - {{[[video]]: https://youtu.be/UY-sAC2eGyI }}
- Doc mode #.hide
    - ```css
.doc-mode > .rm-block__children:not(.rm-heading-level-1)  .rm-multibar {
  border-color: transparent;
}

.doc-mode > .rm-block__self {
  display: none;
}

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

.doc-mode.rm-heading-level-1:hover > .rm-block__children {
  background-color: rgba(211,211,211,0.11);
  border-top: 1px solid grey;
  margin-left: 8px;
}

.doc-moderm-heading-level-2:hover > .rm-block__children {
  background-color: rgba(211,211,211,0.11);
  border-top: 1px solid grey;
  margin-left: 8px;
}

.doc-mode.rm-heading-level-3:hover > .rm-block__children {
  background-color: rgba(211,211,211,0.11);
  border-top: 1px solid grey;
  margin-left: 8px;
}```
- Graph-wide CSS #.hide
    - roam/render
        - ```css
.rm-help-results {
  height: 800px;
}

.rm-help {
  margin-top: 20px;
}```
    - Hide things
        - ```css

.bp3-icon-help {
  display: none;
}```
    - Full-width search c/o [[Jeff Harris]] and [[Daniel van der Merwe]]
        - ```plain text
/* Full Width Search
  Changes the search bar to be full screen width all the time, no animations
*/
.rm-find-or-create-wrapper {
  flex: 0 1 100% !important;
}
.rm-find-or-create-wrapper .bp3-transition-container {
  width: 100%;
}
.rm-find-or-create-wrapper .bp3-menu {
  max-width: none;
  max-height: 400px;
}
.rm-find-or-create-wrapper .rm-menu-item {
  border-radius: 2px;
  cursor: pointer;
  padding: 6px;
}
.rm-find-or-create-wrapper .rm-menu-item .rm-search-title {
  font-weight: bold;
}
.rm-find-or-create-wrapper .rm-menu-item .rm-search-title .rm-new-page {
  color: var(--rm-search__color_new-page);
}
.rm-find-or-create-wrapper .rm-menu-item .rm-search-list-item {
  color: var(--rm-search__color_body);
  margin-left: -20px;
  overflow-wrap: break-spaces;
  word-break: break-word;
}```
    - Full-width text blocks
        - ```css
```
    - Grid
        - ```css
.roam-block-container[data-page-links*=".rm-grid"] .rm-block-children {
  display: grid;
  margin-left: 0px;
  grid-template-columns: repeat( auto-fit, minmax(150px, 1fr) );
  max-width: 550px;
}

span[data-tag=".rm-grid"] {
  display: none !important;
}

.box .rm-block-text {
  padding: 10px;
  font-size: 13px !important;
  border: 1px solid #5C7080 !important;
  border-radius: 2px;
  max-width: 80%;
  margin-bottom: 10px;
  margin-top: 10px;
  text-align: center;
}

span[data-tag=".box"] {
  display: none !important;
}

.roam-block-container[data-page-links*=".rm-grid"] .rm-multibar {
  display: none;
}
```
    - Hide twitter stuff #.hide
        - ```css
.dont-focus-block > sub, .dont-focus-block > button {
  display: none;
  display: none;
}```
    - ```css
.rm-sidebar-outline > div:nth-child(1) {
  margin-bottom: 16px;
}```
