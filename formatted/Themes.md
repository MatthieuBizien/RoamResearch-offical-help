#.doc-mode
    - ### [Request to be featured](https://roamresearch.typeform.com/to/g5W8uCqz)
    - ### Applying Custom Themes to you Graph by [Conor White-Sullivan](<Conor White-Sullivan.md>)
        - {{[video](<video.md>): https://youtu.be/UY-sAC2eGyI }}
    - ## **Team Favorites**
        - ### ["Advaita" aka Better Dark Age / Dracula Pro](<"Advaita" aka Better Dark Age / Dracula Pro.md>)
            - **[Screenshots](<Screenshots.md>):**
                - Dracula Pro
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2FpHrno4MPZY.png?alt=media&token=608fcfc3-3338-4f57-ab6d-c93b51c1ee9d)
            - **[Last updated](<Last updated.md>):** [December 30th, 2020](<December 30th, 2020.md>)
            - **[Designer](<Designer.md>):** [Abhay Prasanna](<Abhay Prasanna.md>)
                - **[Twitter](<Twitter.md>):** [@AbhayPrasanna](https://twitter.com/AbhayPrasanna)
                - Love this theme? Say thanks via [PayPal](https://www.paypal.me/abhayprasanna) or Venmo @Abhay-Prasanna (all proceeds reinvested in the Roam community!)
            - **[Special Features](<Special Features.md>):**
                - Very responsive to CSS changes (update within 24 hours)
                - Multiple Dark Colorsets
                    - Material Palenight
                        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2FTKRjaiLAWr.png?alt=media&token=d1e081e4-61ec-48a1-a7b4-5bd3152e59df)
                    - Dark Night
                        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2F_XwEZNszZy.png?alt=media&token=44c6974a-ad96-4a79-870d-68563ff2f8cc)
                    - Shades of Purple
                        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2FWz9h4gySQQ.png?alt=media&token=79399141-5054-4832-8971-057ee944fc8a)
                - Switches to Light mode based on OS setting
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2FTzMglEX3y3.png?alt=media&token=d0ffefe9-e9d9-4429-8f17-d7edae5a4dfb)
                - Masonry add-on
                    - Pages stack in columns in sidebar
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2F7kcdEQWEBM.png?alt=media&token=e2f32302-310d-4619-a80d-27c48066dbd6)
                - Rainbow indents add-on
                    - Colorful shadowed indent levels
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2FksQEhPdk3w.png?alt=media&token=27cc4bd1-b2c1-46ba-b757-31e50da5e957)
            - **[Code](<Code.md>):**
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
@import url('https://abhayprasanna.github.io/material-palenight-roam.css');
@import url('https://abhayprasanna.github.io/rainbow-indent.css');
@import url('https://abhayprasanna.github.io/dark-masonry.css') (min-width:700px);```
                - Replace "dark-age-dracula" with the following for other colorsets:
                    - material-palenight-roam [*](((NfZ-xipBw)))
                    - dark-night-roam [*](((MAx6iJEHs)))
                    - shades-of-purple [*](((iwbzGyhHg)))
                - Various optional adjustments I use in my own theme (annotated in code):
                    - {{[roam/css](<roam/css.md>)}}
                        - ```css
@import url('https://abhayprasanna.github.io/optional.css');```
        - ### [Railscast](<Railscast.md>)
            - **[Screenshots](<Screenshots.md>):**
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froamcss%2F866sLcv-ZR.png?alt=media&token=7656688e-3cf9-4d05-9636-16e0ec5eed96)
            - **[Last updated](<Last updated.md>):** [January 6th, 2021](<January 6th, 2021.md>)
            - **[Designer](<Designer.md>):** [Jeff Harris](<Jeff Harris.md>)
                - **[Twitter](<Twitter.md>):** [@jeffharrissays](https://twitter.com/jeffharrissays)
                - Love this theme? Say thanks via [Cash App](https://cash.app/$jeffharris) or [paypal](https://paypal.me/jmharris903?locale.x=en_US)
            - **[Special Features](<Special Features.md>):**
                - Robust variables for customization
                    - {{[roam/css](<roam/css.md>)}}
                        - ```css

:root {
  /* Roam default variables */

  --primary-color: [137cbd](<137cbd.md>);
  --s1: 8px;
  --background-color: [e1e8ed](<e1e8ed.md>);

  /* Primary fonts */

  --main-font: 'Inter', sans-serif;
  --main-font-color: [999](<999.md>);
  --main-font-size: 14px;
  --code-font: 'Source Code Pro', 'Courier New', Courier, monospace;
  --code-font-color: [6d9cbe](<6d9cbe.md>);
  --code-font-size: 0.9rem;
  --caret-color: [0080ff](<0080ff.md>);

  /* Fonts */

  --alias-bg: transparent;
  --alias-font-color: [fecf2b](<fecf2b.md>);
  --attr-font-color: rgba(17, 137, 189, 0.65);
  --block-ref-bg: none;
  --block-ref-border: rgba(254, 207, 43, 0.6);
  --block-ref-font-size: 1em;
  --block-ref-hover: [eb9854](<eb9854.md>);
  --block-ref-hover-bg: [111](<111.md>);
  --breadcrumb-bg: transparent;
  --breadcrumb-color: [5c7080](<5c7080.md>);
  --breadcrumb-font-size: 13px;
  --breadcrumb-line-height: 0.85em;
  --calculation-color: [ff6000](<ff6000.md>);
  --db-menu-bg: [333](<333.md>);
  --db-menu-border: [3d3d3d](<3d3d3d.md>);
  --db-menu-header: [5c7080](<5c7080.md>);
  --db-menu-item: [eb9854](<eb9854.md>);
  --db-title-font-color: [eb9854](<eb9854.md>);
  --db-title-hover: rgba(167, 182, 194, 0.3);
  --dialog-bg: [333](<333.md>);
  --dialog-font-color: [eee](<eee.md>);
  --emphasis: [fc5963](<fc5963.md>);
  --external-link-color: [8dbb40](<8dbb40.md>);
  --h1-font: var(--main-font);
  --h1-font-color: [1189bd](<1189bd.md>);
  --h1-font-size: 2.25em;
  --h1-font__link--color: var(--page-link-color);
  --h2-font: var(--h1-font);
  --h2-font-color: [1189bd](<1189bd.md>);
  --h2-font-size: 1.625em;
  --h2-font__link--color: var(--page-link-color);
  --h3-font: var(--h1-font);
  --h3-font-color: [1189bd](<1189bd.md>);
  --h3-font-size: 1.2rem;
  --h3-font__link--color: var(--page-link-color);
  --hashtag: [e9892475](<e9892475.md>);
  --highlight-background-color: [008aff5e](<008aff5e.md>);
  --highlight-font-color: [bbb](<bbb.md>);
  --highlight-link-color: [ff6000](<ff6000.md>);
  --left-sidebar-font-color: [1189bd](<1189bd.md>);
  --left-sidebar-font-color-hover: [e98924](<e98924.md>);
  --left-sidebar-font-size: 1rem;
  --left-sidebar-shortcuts-color: var(--left-sidebar-font-color);
  --left-sidebar-shortcuts-font-size: 1rem;
  --left-sidebar-shortcuts-title-color: var(--left-sidebar-font-color);
  --page-brackets: rgba(228, 124, 67, 0.25);
  --page-link-color: [eb9854](<eb9854.md>);
  --page-link-namespace-color: [ebd454](<ebd454.md>);
  --popover-font-color: [e98924](<e98924.md>);
  --popover-bg: [333](<333.md>);
  --ref-count-font-size: 0.8em;
  --right-sidebar-font-color: var(--main-font-color);
  --right-sidebar-link-color: [eb9854](<eb9854.md>);
  --right-sidebar-bg: [323232](<323232.md>);
  --right-sidebar-masonry-bg: var(--body-bg);
  --right-sidebar-masonry-outline: [3d3d3d](<3d3d3d.md>);
  --right-sidebar-section-border-color: [e9892475](<e9892475.md>);
  --search-bg: [252525](<252525.md>);
  --search-body-font-color: [8a9ba8](<8a9ba8.md>);
  --search-font-color: [af671c](<af671c.md>);
  --search-new-page-color: [8dbb40](<8dbb40.md>);
  --search-outline: [e9892475](<e9892475.md>);
  --search-selected-row: [4c4c4c](<4c4c4c.md>);
  --strong: [508bb5](<508bb5.md>);
  --tag-font-color: [777](<777.md>);
  --tag-font-color-hover: [fff](<fff.md>);
  --tag-hover-bg: [e98924](<e98924.md>);
  --tag-padding: 0.071428571em 0.428571429em 0.214285714em;
  --tag-radius: 2em;

  /* Backgrounds and objects */

  --block-highlight: [00588e](<00588e.md>);
  --block-highlight-current: rgba(255, 255, 255, 0.05);
  --block-highlight-bg: [312c28](<312c28.md>); // This is the Mentions background highlight color
  // --body-bg: [232323](<232323.md>);
  --body-bg: [2c2c2c](<2c2c2c.md>);
  --bullet: rgba(225, 117, 28, 0.3);
  --bullet-closed: rgba(225, 117, 28, 1);
  --bullet-closed-right-sidebar: var(--bullet-closed);
  --bullet-outline: [404040](<404040.md>);
  --bullet-outline-highlight: [ff9500](<ff9500.md>);
  --bullet-outline-hover: [ff9500b3](<ff9500b3.md>); //recommend this be 70% of --bullet-outline-highlight
  --bullet-position: 4px;
  --bullet-version: [137cbd](<137cbd.md>);
  --checkmark-border: [137cbd](<137cbd.md>);
  --checkmark-bg: [555](<555.md>);
  --checkmark-color: [137cbd](<137cbd.md>);
  --code-bg: [002b36](<002b36.md>);
  --datepicker-bg: transparent;
  --datepicker-day-wrapper: [d9822b7a](<d9822b7a.md>);
  --datepicker-font-color: var(--popover-font-color);
  --datepicker-select-bg: [444](<444.md>);
  --hr: rgba(225, 117, 28, 0.5);
  --icon-bg-hover: rgba(167, 182, 194, 0.3);
  --icon-color: [e78924](<e78924.md>);
  --icon-color-hover: [e78924](<e78924.md>);
  --inline-search-bg: [333](<333.md>);
  --inline-comment-bg: transparent;
  --inline-comment-bg-hover: var(--reference-item-bg);
  // --left-sidebar-bg: [2b2b2b](<2b2b2b.md>);
  --left-sidebar-bg: [323232](<323232.md>);
  --left-sidebar-hover-bg: [1f1f1f](<1f1f1f.md>);
  --reference-item-bg: [d8ac6e1a](<d8ac6e1a.md>); // JH: Railscast uses 1 semi-transparent color for all three bg values
  --reference-item-bg-2: [d8ac6e1a](<d8ac6e1a.md>);
  --reference-item-bg-3: [d8ac6e1a](<d8ac6e1a.md>);
  --section-border-color: [e9892475](<e9892475.md>);
  --select-bg: [232323](<232323.md>);
  --topbar-bg: var(--body-bg);
  --topbar-border-color: [333](<333.md>);

  /* Misc */

  --pages-delete-bg: [222](<222.md>); // modal variable
  --pages-delete-border-color: [d8e1e8](<d8e1e8.md>); // JH: modal variable, New variable TODO add to body .delete-all-dialog-items
  --pages-header-row-bg: [262626](<262626.md>);
  --pages-header-row-font-color: [bfccd6](<bfccd6.md>);
  --pages-mentions-bg-empty: [3a3a3a](<3a3a3a.md>);
  --pages-mentions-color: [ff6000](<ff6000.md>);
  --pages-mentions-color-empty: [737373](<737373.md>);
  --pages-row-highlight: [292929](<292929.md>);
  --pages-search-bg: [3a3a3a](<3a3a3a.md>);
  --pages-search-outline: [e9892475](<e9892475.md>);
  // --pages-search-outline: var(--search-outline); //no longer exists in Roam, add if needed for Theme or replace with inherit or initial?
  --pages-table-border: [2f373d](<2f373d.md>);
  --pages-sorted-color: [508bb5](<508bb5.md>);

  --table-border: [444](<444.md>);
  --table-font-size: 0.85rem;

  --kanban-board-bg: [333333](<333333.md>);
  --kanban-card-bg: [555555](<555555.md>);
  --kanban-card-font-color: [6d9cbe](<6d9cbe.md>);
  --kanban-column-bg: [454545](<454545.md>);
  --kanban-column-font-color: [e98924](<e98924.md>);

  --encrypted-font-color: [ff6000](<ff6000.md>);
  --encrypted-bg: [222](<222.md>);

  --pomodoro-bg: transparent;
  --pomodoro-color: [fc5963](<fc5963.md>);
  --pomodoro-border: [fc596370](<fc596370.md>);

  --blockquote-font-color: rgba(109, 156, 190, 0.89);
  --blockquote-font-size: 14px;
  --blockquote-border-color: [30404d](<30404d.md>);
  --blockquote-bg: none;
  --blockquote-cite: [777](<777.md>);

  --emoji-bg: [2d2d2d](<2d2d2d.md>);
  --emoji-border: rgba(225, 117, 28, 0.4);
  --emoji-color: [aaa](<aaa.md>);

  --no-query-results: 'Query returned no results';
  --no-query-results-color: [fc5963](<fc5963.md>);
  --query-results-border: [f2c98f1a](<f2c98f1a.md>);

  --q1: [50b2c0](<50b2c0.md>);
  --q2: [c5d86d](<c5d86d.md>);
  --q3: [ff6b6b](<ff6b6b.md>);
  --q4: [ca7d4a](<ca7d4a.md>);

  /* Scrollbar settings - to disable set values to none */

  --scrollbar-thumb: [323232](<323232.md>);
  --scrollbar-track: rgba(153, 153, 153, 0.1);

  /* Saving icon colors */

  --saving-local: [99280f](<99280f.md>);
  --saving-remote: [d9822b](<d9822b.md>);
  --synched: [0f9960](<0f9960.md>);```
                - Customize query display
                    - MINIMIZE QUERIES: add any one of the following tags before the beginning of your query (in the same block): [min-title](<min-title.md>) = hides the page reference link / page title [min-con](<min-con.md>) = hides the contextual reference information (breadcrumbs) [minimal](<minimal.md>) = hides both the title and the context [min-q](<min-q.md>) = hides the query string, similar to legacy behavior [min-all](<min-all.md>) = hides everything — title, context, and query string
                - Expanded Bullet collapse
                - Fullwidth search bar
            - **[Code](<Code.md>):**
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
@import url('https://jmharris903.github.io/Railscast-for-Roam-Research-Theme/RailsRoam.css');```
        - ### [Better Roam Research](<Better Roam Research.md>)
            - **[Screenshots](<Screenshots.md>):**
                - If your OS is in Light Mode:
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FnoeJ9L0SQp.png?alt=media&token=dcfd7281-104d-4fbc-b88b-0f93de7c4f4f)
                - If your OS is in Dark Mode:
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2FqEbHtYl5zg.png?alt=media&token=50a57675-7928-450a-b53d-23a4f5c276fc)
            - **[Designer](<Designer.md>):** [Fabrizio Rinaldi](<Fabrizio Rinaldi.md>)
                - **[Twitter](<Twitter.md>):** [@linuz90](https://twitter.com/linuz90)
                - Love this theme? Say thanks via [Paypal](https://www.paypal.me/linuz90)
            - **[Special Features](<Special Features.md>):**
                - #[Dark Mode](<Dark Mode.md>) but only if your OS is set to dark! 
            - **[Code](<Code.md>):**
                - Last updated [June 4th, 2020](<June 4th, 2020.md>). If it's been a while, you can check [Github](https://github.com/linuz90/better-roam-research) for the latest version. 
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
:root {
  --font-size: 15.5px;
  --border-color: rgba(0, 0, 0, 0.08);
  --subtle-border-color: rgba(0, 0, 0, 0.05);
  --main-background-color: hsl(210, 9%, 98%);
  --body-background-color: [ffffff](<ffffff.md>);
  --reference-item-background: hsl(0, 0%, 99%);
  --brackets-color: rgba(0, 0, 0, 0.25);
  --empty-text-color: hsl(203, 12%, 75%); }

.rm-title-untitled,
[block-input-ghost](<block-input-ghost.md>) > span,
textarea::placeholder {
  color: var(--empty-text-color) !important; }

body,
div,
textarea,
.level2 {
  font-family: 'Quattro', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif !important; }

iframe {
  border: none !important; }

.loading-astrolabe {
  position: absolute !important;
  width: 80px !important;
  height: 80px !important;
  opacity: 0.3 !important;
  top: calc(50% - 40px) !important;
  left: calc(50% - 40px) !important; }

[roam-sidebar-logo](<roam-sidebar-logo.md>) {
  display: none !important; }

body,
[app](<app.md>) {
  background: var(--main-background-color) !important; }

.roam-center {
  border-left: 1px solid var(--border-color) !important;
  border-top: 1px solid var(--border-color) !important;
  border-right: 1px solid var(--border-color) !important;
  border-radius: 6px;
  box-shadow: 0px 2px 14px rgba(0, 0, 0, 0.04) !important;
  overflow: visible !important;
  background: var(--body-background-color) !important;
  margin-top: 10px;
  margin-right: 16px;
  margin-left: 16px; }
  .roam-center > div:first-child {
    padding-right: calc(0.5 * (100% - 820px)) !important;
    padding-left: calc(0.5 * (100% - 820px)) !important; }

.roam-topbar {
  background: var(--main-background-color) !important; }
  .roam-topbar input[find-or-create-input](<find-or-create-input.md>) {
    box-shadow: none !important;
    border: 1px solid var(--border-color) !important; }

.roam-body,
.roam-topbar,
[right-sidebar](<right-sidebar.md>),
.roam-sidebar-container {
  background: transparent !important; }

[right-sidebar](<right-sidebar.md>) {
  border: none !important;
  transition: none !important;
  overflow: hidden !important; }
  [right-sidebar](<right-sidebar.md>) h1 {
    font-size: 18px !important; }
  [right-sidebar](<right-sidebar.md>) [roam-right-sidebar-content](<roam-right-sidebar-content.md>) > div[style] {
    border-bottom: 1px solid var(--subtle-border-color) !important; }
  [right-sidebar](<right-sidebar.md>) .hoverparent,
  [right-sidebar](<right-sidebar.md>) .react-resizable {
    max-width: 100% !important; }
    [right-sidebar](<right-sidebar.md>) .hoverparent img,
    [right-sidebar](<right-sidebar.md>) .react-resizable img {
      max-width: 100% !important; }

.rm-page-ref-tag {
  color: [9099a1](<9099a1.md>) !important; }

span.checkmark {
  top: -2px; }

.rm-level1 div,
.rm-level1 textarea {
  font-size: 22px !important;
  line-height: 1.5 !important; }

.rm-level2 div,
.rm-level2 textarea {
  font-size: 20px !important;
  line-height: 1.5 !important; }

.rm-level3 div,
.rm-level3 textarea {
  font-size: 18px !important;
  line-height: 1.5 !important; }

.level2 {
  font-weight: inherit !important; }

.roam-log-container .roam-log-page {
  border-top: 1px solid var(--subtle-border-color) !important; }
  .roam-log-container .roam-log-page:first-child {
    min-height: 0 !important;
    border-top: none !important; }

.rm-reference-item {
  background: var(--reference-item-background) !important;
  border: 1px solid [f0f0f0](<f0f0f0.md>) !important;
  border-radius: 6px !important;
  padding: 8px 10px 8px 2px !important; }
  .rm-reference-item .rm-block-text {
    font-size: var(--font-size) !important; }

.CodeMirror {
  font-size: 13px !important; }

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button:hover,
.roam-body
.roam-app
.roam-sidebar-container
.roam-sidebar-content
.starred-pages-wrapper
.starred-pages
.page:hover {
  color: inherit !important;
  background-color: transparent !important; }

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper,
.roam-body
.roam-app
.roam-sidebar-container
.roam-sidebar-content
.starred-pages-wrapper
.starred-pages
.page,
.bp3-minimal > div {
  color: [666666](<666666.md>) !important;
  font-size: 13px !important; }

.roam-sidebar-content {
  padding: 0 !important; }
  .roam-sidebar-content > div:not(.log-button):not(:first-child) {
    padding: 0 !important; }
  .roam-sidebar-content > div:first-child {
    padding-bottom: 18px !important; }

.starred-pages-wrapper > div:first-child {
  display: none; }
.starred-pages-wrapper .flex-h-box,
.starred-pages-wrapper .flex-h-box span {
  font-size: 13px !important;
  opacity: 0.6 !important; }

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button,
.roam-body
.roam-app
.roam-sidebar-container
.roam-sidebar-content
.starred-pages-wrapper
.starred-pages
.page {
  padding: 6px 24px 6px !important; }

.bp3-icon-small {
  padding-left: 24px !important; }

.rm-block-text {
  max-width: 640px !important;
  font-size: var(--font-size) !important; }

.block-bullet-view {
  margin-bottom: 3px !important; }

.roam-article > div > div h1 {
  font-size: 26px !important;
  font-weight: 700 !important;
  height: auto !important;
  line-height: 1.5 !important; }

.rm-title-display,
.rm-title-textarea {
  height: auto !important;
  line-height: 1.5 !important; }

.roam-log-container .roam-log-preview h1 {
  font-size: 22px !important;
  font-weight: 700 !important; }

strong {
  font-weight: 700 !important; }

.block-border-left {
  border-left-color: var(--subtle-border-color) !important; }

.rm-reference-main div > strong {
  color: gray !important; }

@media (prefers-color-scheme: dark) {
  body {
    background: [171717](<171717.md>) !important; }

  [app](<app.md>) {
    filter: invert(1) hue-rotate(180deg) !important; }

  img,
  div[buffer](<buffer.md>),
  .bp3-portal,
  .intercom-app,
  .loading-astrolabe,
  .bp3-dialog,
  .twitter-tweet,
  iframe {
    filter: invert(1) hue-rotate(180deg) !important; }

  .roam-highlight {
    background-color: [e2cb47](<e2cb47.md>) !important; }

  .bp3-overlay-backdrop {
    background-color: rgba(255, 255, 255, 0.7) !important; }

  :root {
    --border-color: rgba(0, 0, 0, 0.07) !important;
    --subtle-border-color: rgba(0, 0, 0, 0.05) !important;
    --main-background-color: hsl(0, 0%, 96%) !important;
    --body-background-color: hsl(0, 0%, 90%) !important;
    --reference-item-background: hsl(0, 0%, 93%) !important;
    --brackets-color: rgba(0, 0, 0, 0.3) !important;
    --empty-text-color: hsl(203, 5%, 70%); } }```
        - ### [Leyendecker](<Leyendecker.md>)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2Ffc9tIphX_X.png?alt=media&token=f6c09e01-742a-478d-a537-0b3a88796325)
            - **[Designer](<Designer.md>):** [Maggie Appleton](<Maggie Appleton.md>)
                - **[Twitter](<Twitter.md>):** [@mappletons](https://twitter.com/mappletons)
                - Love this theme? Say thanks via [Paypal](https://paypal.me/maggieappleton)
            - **[Special Features](<Special Features.md>):**
                - Queries and Kanbans got some extra love. 
                - Custom data-tags are all at the end of the CSS file, which you'll probably want to edit/customise. 
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2FER9x_LvrLc.png?alt=media&token=4860ec31-f27e-45c7-adaa-194594cc55e2)
            - **[Code](<Code.md>):**
                - Last updated [June 4th, 2020](<June 4th, 2020.md>)
                - [Site-wide](<Site-wide.md>)
                    - {{[roam/css](<roam/css.md>)}}
                        - ```css
h1,
h2,
h3,
h4,
h5,
h6 {
    font-family: "Lato", sans-serif;
    font-size: 3em;
}
div,
textarea {
    font-weight: 400;
    color: [3F4758](<3F4758.md>);
    font-size: 1.002em;
}
.roam-block-container {
    max-width: 1000px;
}

.rm-pomodoro {
    background: [fff](<fff.md>) !important;
    color: [ff4747](<ff4747.md>) !important;
    padding: 4px 14px;
    line-height: 2em;
    font-weight: 600;
    border-radius: 2em;
    border: 1px solid [ff474770](<ff474770.md>);
}

.rm-pomodoro {
    background: [ff6956](<ff6956.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 4px 14px;
    line-height: 2em;
    font-weight: 600;
    border-radius: 2em;
    border: 1px solid [ed5845](<ed5845.md>);
}

.rm-pomodoro::first-letter {
  margin-right: 8px;
}

.rm-query {
    border: 0.5px solid [e4e9ec](<e4e9ec.md>);
    border-radius: 5px;
    
}

.rm-query .rm-query-title {
    background-color: [f7f8f8](<f7f8f8.md>);
    padding: 0.8em;
    color: [d1dbe2](<d1dbe2.md>);
    font-size: 80%;
}

.rm-reference-main.rm-query-content {
    padding: 0.8em;
}

.rm-reference-main .rm-reference-item .rm-block-text {
    font-size: 90%;
}

.rm-ref-page-view-title span {
    
}

.rm-reference-main .rm-reference-item .controls {
    margin-left: -1em;
}

.rm-ref-page-view {
    padding: 0.4em 0.2em;
}

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page {
    padding: 6px;
}

div.flex-v-box.starred-pages-wrapper > div.flex-h-box > span {
    font-size: 14px !important;
    opacity: 80%;
    letter-spacing: 0.04em;
}

div.roam-sidebar-container.noselect > div > div {
    font-size: 14px !important;
    letter-spacing: 0.03em;
    
}

[block-input](<block-input.md>) {
    background: white;
}

.roam-body [block-input](<block-input.md>) > span > div {
    padding: 6px 24px;
    background: white;
}

span.bp3-icon-small.bp3-icon-star {
    display: none;
    visibility: hidden;
}

.roam-block {
    max-width: 850px;
}

[right-sidebar](<right-sidebar.md>) > div {
    background-color: [f7f8fa](<f7f8fa.md>);
    border-left: 1px solid [e9ebef](<e9ebef.md>);
}
.controls .simple-bullet-outer .simple-bullet-inner {
    background-color: [e5e9f2](<e5e9f2.md>);
}
.block-border-left {
    border-left: 1px solid [f3f6f7](<f3f6f7.md>);
}
.kanban-board {
    background-color: [fff](<fff.md>);
}
.kanban-card {
    background-color: white;
    margin: 8px;
    box-shadow: 0px 1px 2px [9eb3c0a8](<9eb3c0a8.md>);
    padding: 10px;
    border-radius: 2px;
    line-height: 1.3em;
}
.kanban-title {
    text-align: center;
    font-weight: 600;
    font-size: 1.1em;
    opacity: 80%;
    color: [485f6f](<485f6f.md>);
    padding-top: 8px;
    border-bottom: 1px solid [c5d1d8](<c5d1d8.md>);
}
.kanban-column {
    background-color: [e7eff3](<e7eff3.md>);
    margin: 0px 4px 0px 4px;
    padding: 4px;
    min-width: 200px;
    border-radius: 3px;
}


.rm-block-ref::before {
    content: '';
    display: inline-block;
    width: 2px;
    border-radius: 40px;
    height: 12px;
    background: [ff913c](<ff913c.md>);
    margin-right: 8px;
}
.rm-block-ref {
    border-bottom: none;
    font-size: 1em;
    color: [515e70](<515e70.md>);
}
.rm-block-ref:hover {
    background: none;
    cursor: pointer;
}
.checkmark {
    background: [fff](<fff.md>);
}
.check-container input:checked ~ .checkmark {
    background: [33bdea](<33bdea.md>);
}
.check-container input:checked ~ .checkmark:after {
    border-color: [fff](<fff.md>);
}
.rm-reference-item {
    margin-top: 8px;
    border-radius: 6px;
    border: 1px solid [e4e9ee](<e4e9ee.md>);
    margin-right: 8px;
    flex: 1 1 100%;
    word-break: break-word;
    background-color: [f7f9fb](<f7f9fb.md>);
    padding: 8px;
}

.rm-level2 {
    font-size: 1.5em;
}
.rm-level3 {
    color: [939aae](<939aae.md>);
    font-weight: 400;
    font-size: 1.3em;
}
.rm-page-ref {
    color: [9aabd0](<9aabd0.md>);
}
.rm-page-ref-link-color {
    color: [ec6f35](<ec6f35.md>);
    font-weight: 600;
}
a {
    color: [8A3CC8](<8A3CC8.md>);
}
.intercom-app,
.intercom-launcher-frame,
[intercom-container](<intercom-container.md>) {
    display: none !important;
}
.roam-body .roam-app .roam-sidebar-container {
    background-color: white;
    border-right: 1px [eee](<eee.md>) solid;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page,
.roam-body .roam-app .roam-sidebar-container > * {
    opacity: 80%;
    box-shadow: none;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page:hover,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button:hover {
    background: white;
    color: black;
    opacity: 100%;
}
[buffer](<buffer.md>).tall {
    height: calc(100vh - 50px) !important;
}
.check-container {
    padding-right: 4px;
}
span.rm-page-ref {
    border-radius: 2px;
    padding-left: 1px;
    padding-right: 1px;
}
.content span.rm-page-ref {
    padding: 4px 1px 1px;
    /* required for fixing azo */
}
.center-proj {
    text-align: center;
}

```
                - [Tag Styles](<Tag Styles.md>)
                    - {{[roam/css](<roam/css.md>)}}
                        - ```css

/* Custom data tags */
span.rm-page-ref[data-tag="Tweet"] {
    background: [81D5ED](<81D5ED.md>) !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Literature Notes"] {
    background: [9769FF](<9769FF.md>) !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}


span.rm-page-ref[data-tag="Evergreens"] {
    background: [0DBAC6](<0DBAC6.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 3px 8px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Seedling"] {
    color: [0dbac6](<0dbac6.md>) !important;
    padding: 3px 3px;
    font-weight: 600;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"] {
    color: [FCB815](<FCB815.md>) !important;
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"]:before {
    content: '✦ '
}

span.rm-page-ref[data-tag="Illustrated Notes"] {
    color: [7172FC](<7172FC.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Garden Notes"] {
    color: [9DBC13](<9DBC13.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Video Tutorial"] {
    color: [db3b8d](<db3b8d.md>);
    padding: 3px 4px;
    line-height: 1.4em;
    font-weight: 700;
}

span.rm-page-ref[data-tag="Essay"] {
    background: [ADCB2A](<ADCB2A.md>);
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}


span.rm-page-ref[data-tag="Livestream"] {
    color: [B979CF](<B979CF.md>);
    padding: 3px 4px;
    line-height: 1.4em;
    font-weight: 700;
}

span.rm-page-ref[data-tag="Talk"] {
    background: [7172FC](<7172FC.md>);
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Waiting"] {
    background: [F9C866](<F9C866.md>);
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Researching"] {
    background: [FF9D66](<FF9D66.md>) !important;
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Synthesising"] {
    background: [FC766F](<FC766F.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}


span.rm-page-ref[data-tag="Alive"] {
    background: [EE5F85](<EE5F85.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}```
        - ### [Zenith](<Zenith.md>)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2FpF2OCzwlH2.png?alt=media&token=4bd42cd5-cd10-49a6-a915-a328ff067467)
            - **[Designer](<Designer.md>):** [Azlen Elza](<Azlen Elza.md>)
                - **[Twitter](<Twitter.md>):** [@azlenelza](https://twitter.com/azlenelza) 
                - Love this theme? Say thanks via [Paypal](https://www.paypal.me/azlenelza). 
                - Also created [Cosmonaut](<Cosmonaut.md>) and [Yggdrasil](<Yggdrasil.md>)
            - **[Special Features](<Special Features.md>):**
                - Collapsible columns -- side-by-side view for items opened in the sidebar 
                - Searchbar appears in main page 
                - Overlay side-by-side view over graph/diagram
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FOAvb9EDHlf.png?alt=media&token=c0737a55-e90a-4f85-baa3-cc4797b24834)
            - **[Code](<Code.md>):**
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
/* IMPORT CORE THEME */
@import url('https://azlen.github.io/roam-themes/core.css');

/* GOOGLE FONTS */
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:ital,wght@0,400;0,700;1,400;1,700&display=swap');	

:root {	
    --page-width: 616px;
    --page-order: row-reverse; /* new pages show up to the right */
    /*--page-order: row; /* new pages show up to the left */
    
    --header-font: "Source Sans Pro", "Inter", sans-serif;	
    --body-font: "Source Sans Pro", "Inter", sans-serif;	
    	
    --bg-color: [EEEEEE](<EEEEEE.md>);	
    --page-color: rgba(255, 255, 255, 0.95);	
    	
    --text-color: [000000](<000000.md>);	
    --icon-color: [5c7080](<5c7080.md>);
    --bullet-color: rgba(0, 0, 0, 0.2);	
    	
    --page-shadow: 0px 8px 14px rgba(0, 0, 0, 0.05);	
    	
    --color-primary: 73, 197, 91;	
    --color-primary-contrast: [FFFFFF](<FFFFFF.md>);	
    --color-secondary: 147, 100, 235;

    --color-secondary-contrast: [FFFFFF](<FFFFFF.md>);	
}

/* CHANGE COLOURS IN CANVAS */
canvas[data-id="layer2-node"] {	
    filter: invert(1) hue-rotate(110deg) saturate(2.5);	
}```
    - ## **Dark Modes**
        - ### [Cosmonaut](<Cosmonaut.md>)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2FZqga3Oe0uc.png?alt=media&token=ca5c4739-ef61-4dea-a241-eaa81a5450bf)
            - **[Designer](<Designer.md>):** [Azlen Elza](<Azlen Elza.md>)
                - **[Twitter](<Twitter.md>):** [@azlenelza](https://twitter.com/azlenelza) 
                - Love this theme? Say thanks via [Paypal](https://www.paypal.me/azlenelza). 
                - Also created [Zenith](<Zenith.md>) and [Yggdrasil](<Yggdrasil.md>)
            - **[Special Features](<Special Features.md>):**
                - #[Dark Mode](<Dark Mode.md>)
                - Variation on [Zenith](<Zenith.md>) which has: 
                    - Collapsible columns -- side-by-side view for items opened in the sidebar 
                    - Searchbar appears in main page 
                    - Overlay side-by-side view over graph/diagram
            - **[Code](<Code.md>):**
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
/* IMPORT CORE THEME */
@import url('https://azlen.github.io/roam-themes/core.css');

/* GOOGLE FONTS */
@import url('https://fonts.googleapis.com/css2?family=Oxanium:wght@600&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,400;0,700;1,400;1,700&display=swap');

/* VARIABLES */
:root {
    --page-width: 616px;
    
    --header-font: "Oxanium", "Inter", sans-serif;
    --body-font: "Ubuntu", "Inter", sans-serif;
    
    --bg-color: [000000](<000000.md>);
    --page-color: rgba(44, 44, 44, 0.95);
    
    --text-color: [FFFFFF](<FFFFFF.md>);
    --icon-color: rgb(102, 102, 102);
    --bullet-color: rgba(255, 255, 255, 0.3);
    
    --page-shadow: 0px 8px 14px rgba(0, 0, 0, 0.25);
    
    --color-primary: 47, 155, 249;
    --color-primary-contrast: [FFFFFF](<FFFFFF.md>);
    --color-secondary: 228, 78, 244;
    
    --color-secondary-contrast: [FFFFFF](<FFFFFF.md>);
}

/* CHANGE COLOURS IN CANVAS */
canvas[data-id="layer2-node"] {
    filter: invert(1) contrast(1.1) hue-rotate(180deg) saturate(2);
}

/* CODE BLOCK STYLING */
/* modified from https://codemirror.net/demo/theme.html[night](<night.md>) */
.CodeMirror { background: var(--bg-color) !important; color: [f8f8f8](<f8f8f8.md>) !important; }
div.CodeMirror-selected { background: [447](<447.md>) !important;  }
.CodeMirror-line::selection, .CodeMirror-line > span::selection, .CodeMirror-line > span > span::selection { background: rgba(68, 68, 119, .99); }
.CodeMirror-line::-moz-selection, .CodeMirror-line > span::-moz-selection, .CodeMirror-line > span > span::-moz-selection { background: rgba(68, 68, 119, .99); }
.CodeMirror-gutters { background: var(--bg-color); border-right: 1px solid [252525](<252525.md>); }
.CodeMirror-guttermarker { color: white !important; }
.CodeMirror-guttermarker-subtle { color: [bbb](<bbb.md>) !important; }
.CodeMirror-linenumber { color: [f8f8f8](<f8f8f8.md>); }
.CodeMirror-cursor { border-left: 1px solid white !important; }
span.cm-qualifier { color: [666666](<666666.md>) !important; }
span.cm-comment { color: [C71FF9](<C71FF9.md>) !important; }
span.cm-atom { color: [B58AFD](<B58AFD.md>) !important; }
span.cm-number, span.cm-attribute { color: [ffd500](<ffd500.md>) !important; }
span.cm-keyword { color: [599eff](<599eff.md>) !important; }
span.cm-string { color: [37f14a](<37f14a.md>) !important; }
span.cm-meta { color: [369BFF](<369BFF.md>) !important; }
span.cm-variable-2, span.cm-tag { color: [99b2ff](<99b2ff.md>) !important; }
span.cm-variable-3, span.cm-def, span.cm-type { color: white !important; }
span.cm-bracket { color: [8da6ce](<8da6ce.md>) !important; }
span.cm-builtin, pan.cm-special { color: [ff9e59](<ff9e59.md>) !important; }
span.cm-link { color: [845dc4](<845dc4.md>) !important; }
span.cm-error { color: [F41000](<F41000.md>) !important; }
.CodeMirror-activeline-background { background: [1C005A](<1C005A.md>) !important; }
.CodeMirror-matchingbracket { outline:1px solid grey !important; color:white !important; }```
    - ## **Feature Expansions**
        - ### Nested Links
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2Fqr3tGRCd-s.png?alt=media&token=31913a3e-546a-4955-87fe-2c9ad8fd160f)
            - **[Designer](<Designer.md>):** [Cato Minor](<Cato Minor.md>)
                - **[Twitter](<Twitter.md>):** [@CatoMinor3](https://twitter.com/CatoMinor3)
                - Love this theme? Say thanks via [Paypal](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6AMGMUDRX29XU&source=url)
            - **[Special Features](<Special Features.md>):**
                - Additional underlining for nested tags 
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2FNRBiiUtnF-.png?alt=media&token=233612e7-2aeb-4d13-b28e-8b9cc806d173)
            - **[Code](<Code.md>):**
                - Last updated [June 4th, 2020](<June 4th, 2020.md>)
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
:root {
    --custom-background-color: lightsteelblue;
    --custom-background-color-hover: orange;
    }


.rm-page-ref-link-color{
   color:black !important;
    background: linear-gradient(0deg, var(--custom-background-color) 2px, white 1px, transparent 1px);
    background-position: 0 100%;
    line-height: 24px;
    padding-bottom: 4px;
}

.rm-page-ref-link-color:hover{
   color:black !important;
    background: linear-gradient(0deg, var(--custom-background-color-hover) 2px, white 1px, transparent 1px);
    background-position: 0 100%;
    text-decoration: none;
    line-height: 24px;
    padding-bottom: 4px;
}

.rm-page-ref-link-color .rm-page-ref-link-color {
color: black !important;
  background: linear-gradient(0deg, var(--custom-background-color) 2px, white 1px, transparent 1px);
    background-position: 0 100%;
   line-height: 28px;
    padding-bottom: 8px;
}

.rm-page-ref-link-color .rm-page-ref-link-color:hover {
color: black !important;
  background: linear-gradient(0deg, var(--custom-background-color-hover) 2px, white 1px, transparent 1px);
    background-position: 0 100%;
   line-height: 28px;
    padding-bottom: 8px;
}


.rm-page-ref-link-color .rm-page-ref-link-color .rm-page-ref-link-color {
color: black !important;
background: linear-gradient(0deg, var(--custom-background-color) 2px, white 1px, transparent 1px);
    background-position: 0 100%;
   line-height: 32px;
    padding-bottom: 12px;
}


.rm-page-ref-link-color .rm-page-ref-link-color .rm-page-ref-link-color:hover {
color: black !important;
background: linear-gradient(0deg, var(--custom-background-color-hover) 2px, white 1px, transparent 1px);
    background-position: 0 100%;
   line-height: 32px;
    padding-bottom: 12px;
}```
    - ## **More Colors**
        - ### [Yggdrasil](<Yggdrasil.md>)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Froam%2FT0iQmFOXwm.png?alt=media&token=3cdca40f-d2bb-4217-9f26-b44c825f88be)
            - **[Designer](<Designer.md>):** [Azlen Elza](<Azlen Elza.md>)
                - **[Twitter](<Twitter.md>):** [@azlenelza](https://twitter.com/azlenelza) 
                - Love this theme? Say thanks via [Paypal](https://www.paypal.me/azlenelza). 
                - Also created [Cosmonaut](<Cosmonaut.md>) and [Zenith](<Zenith.md>)
            - **[Special Features](<Special Features.md>):** 
                - Collapsible columns -- side-by-side view for items opened in the sidebar 
                - Searchbar appears in main page 
                - Overlay side-by-side view over graph/diagram
            - **[Code](<Code.md>):**
                - {{[roam/css](<roam/css.md>)}}
                    - ```css
/* IMPORT CORE THEME */
@import url('https://azlen.github.io/roam-themes/core.css');

/* GOOGLE FONTS */
@import url('https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@0,400;0,700;1,400;1,700&display=swap');

/* VARIABLES */
:root {
    --page-width: 616px;
    
    --header-font: "Crimson Text", serif;
    --body-font: "Crimson Text", serif;
    
    --bg-color: [f5f1e2](<f5f1e2.md>);
    --page-color: rgba(236, 231, 209, .95);
    
    --text-color: [000000](<000000.md>);
    --icon-color: [5c7080](<5c7080.md>);
    --bullet-color: rgba(0, 0, 0, 0.2);
    
    --page-shadow: 0px 8px 14px rgba(0, 0, 0, 0.02);
    --color-primary: 181, 124, 38;
    --color-primary-contrast: [FFFFFF](<FFFFFF.md>);
    --color-secondary: 100, 181, 38;
    
    --color-secondary-contrast: [FFFFFF](<FFFFFF.md>);
}

/* YGGDRASIL CUSTOM STYLES */

.rm-page-ref-tag {
    padding: 3px 6px 2px 6px;
}

/* reverse colours for saving / saving-remote so that green is used for "saved" */
.rm-saving-icon .rm-synced {
    background-color: rgb(var(--color-secondary));
}
.rm-saving-icon .rm-saving-remote {
    background-color: rgb(var(--color-primary));
}

.block-bullet-view .bp3-button:not([class*="bp3-icon"]) {
    padding: 5px 14px 0px 14px!important;
}

.kanban-card {
    box-shadow: 0px 1px 2px rgba(0,0,0, 0.3);
}
.kanban-column {
    background-color: var(--bg-color);
}

/* CHANGE COLOURS IN CANVAS */

canvas[data-id="layer2-node"] {
    filter: invert(1) hue-rotate(170deg) saturate(2.5);
}```
    - ## **Block Level Customizations**
        - from [Maggie Appleton](<Maggie Appleton.md>) in [Leyendecker](<Leyendecker.md>)
            - [Tag Styles](<Tag Styles.md>)
                - {{[roam/css](<roam/css.md>)}}
                    - ```css

/* Custom data tags */
span.rm-page-ref[data-tag="Tweet"] {
    background: [81D5ED](<81D5ED.md>) !important;
    color: white !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Literature Notes"] {
    background: [9769FF](<9769FF.md>) !important;
    color: white !important;
    padding: 3px 7px;
    font-weight: 500;
    line-height: 2em;
}


span.rm-page-ref[data-tag="Evergreens"] {
    background: [0DBAC6](<0DBAC6.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 3px 8px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Seedling"] {
    color: [0dbac6](<0dbac6.md>) !important;
    padding: 3px 3px;
    font-weight: 600;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"] {
    color: [FCB815](<FCB815.md>) !important;
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Idea Bank"]:before {
    content: '✦ '
}

span.rm-page-ref[data-tag="Illustrated Notes"] {
    color: [7172FC](<7172FC.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Garden Notes"] {
    color: [9DBC13](<9DBC13.md>);
    padding: 3px 4px;
    font-weight: 700;
    line-height: 1.4em;
}

span.rm-page-ref[data-tag="Video Tutorial"] {
    color: [db3b8d](<db3b8d.md>);
    padding: 3px 4px;
    line-height: 1.4em;
    font-weight: 700;
}

span.rm-page-ref[data-tag="Essay"] {
    background: [ADCB2A](<ADCB2A.md>);
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}


span.rm-page-ref[data-tag="Livestream"] {
    color: [B979CF](<B979CF.md>);
    padding: 3px 4px;
    line-height: 1.4em;
    font-weight: 700;
}

span.rm-page-ref[data-tag="Talk"] {
    background: [7172FC](<7172FC.md>);
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Waiting"] {
    background: [F9C866](<F9C866.md>);
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Researching"] {
    background: [FF9D66](<FF9D66.md>) !important;
    color: [fff](<fff.md>);
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}

span.rm-page-ref[data-tag="Synthesising"] {
    background: [FC766F](<FC766F.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}


span.rm-page-ref[data-tag="Alive"] {
    background: [EE5F85](<EE5F85.md>) !important;
    color: [fff](<fff.md>) !important;
    padding: 3px 7px;
    line-height: 2em;
    font-weight: 500;
}```

# Backlinks
## [Roam Depot](<Roam Depot.md>)
# [Themes]([Themes](<Themes.md>))

## [roam/css](<roam/css.md>)
- Check out our [community-built themes for inspiration]([Themes](<Themes.md>))

