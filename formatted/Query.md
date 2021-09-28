- #.doc-mode
    - # **Types of queries**
        - ### **and**
            - Find all blocks matching multiple conditions – i.e. blocks or their parents containing multiple page or block references.
            - `{{query: {and: [page A](<page A.md>) [page B](<page B.md>) }}}
{{query: {and: [articles](<articles.md>) ((block)) }}}
{{query: {and: [Tyler Cowen](<Tyler Cowen.md>) ((block)) [econ](<econ.md>) }}}
`
        - ### **or**
            - Find all blocks matching any of a number of conditions – i.e. blocks or their parents containing any of the selected page or block references.

            - `{{query: {or: [page A](<page A.md>) [page B](<page B.md>) }}}
{{query: {or: [Zen](<Zen.md>) [Buddhism](<Buddhism.md>) }}}
{{query: {or: [Utah](<Utah.md>) [Idaho](<Idaho.md>) [Montana](<Montana.md>) }}}
`
        - ### **not**
            - Exclude blocks matching any of the page or block references selected.
            - `{{query: {and: [page A](<page A.md>) {not: [page B](<page B.md>) }}}}
{{query: {and: [Slate Star Codex](<Slate Star Codex.md>) {not: [psychiatry](<psychiatry.md>) }}}}`
        - ### **between**
            - Finds all blocks on daily pages and blocks mentioning a date between two days. ^^**This only works on Daily Notes page**^^.
            - You can use the following as a shorthand: [today](<today.md>), [tomorrow](<tomorrow.md>), [yesterday](<yesterday.md>), [last week](<last week.md>), [next week](<next week.md>), [last month](<last month.md>), and [next month](<next month.md>). 
            - `{{query: {between: [January 1st, 2021](<January 1st, 2021.md>) [today](<today.md>) }}
{{query: {and: [mistakes](<mistakes.md>) {between: [January 1st, 2020](<January 1st, 2020.md>) [December 31st, 2020](<December 31st, 2020.md>) }}}}
{{query: {and: [TODO](<TODO.md>) {between: [last week](<last week.md>) [today](<today.md>) }}}}`
    - **[## Community Videos](<## Community Videos.md>):**
        - ### Query syntax and logic: how to ask Roam questions with queries by [Robert Haisfield](<Robert Haisfield.md>)
            - {{[video](<video.md>): https://www.youtube.com/watch?v=LJZBGJOzhUY&t=20s&ab_channel=RobertHaisfield}}
        - ### How Queries Work in Roam Research by [R.J. Nestor](<R.J. Nestor.md>)
            - {{[video](<video.md>): https://www.youtube.com/watch?v=lBmklV0n8D0}}
        - ### Roam Research Search Queries by [David Perell](<David Perell.md>)
            - {{[video](<video.md>): https://www.youtube.com/watch?v=HoccqyiHvPw}}
        - ### Insight Hunting with Queries in Roam by [Cortex Futura](<Cortex Futura.md>)
            - {{[video](<video.md>): https://www.youtube.com/watch?v=gLAlQGM_l1Q}}
        - ### Roam Research Query Tutorial: Pending Tasks for Task Management and Task Dashboard Using Queries by [The Upgraded Brain](<The Upgraded Brain.md>)
            - {{[video](<video.md>): https://www.youtube.com/watch?v=Kg5omIyWu8s}}
    - **[## Articles](<## Articles.md>):**
        - ### [How to query in Roam](https://roamhacks.com/how-to-query-roam/) by [Roamhacks](<Roamhacks.md>)
        - ### [Searching Roam With Queries: A Primer](https://www.roamstack.com/roam-queries-primer/) by [RoamStack](<RoamStack.md>)
    - **[## Key Commands](<## Key Commands.md>):**
        - `/query`

# Backlinks
## [ Commands](< Commands.md>)
- [Query](<Query.md>)

## [Beginner's Guide](<Beginner's Guide.md>)
- #[Daily Notes](<Daily Notes.md>) | #[Bidirectional linking](<Bidirectional linking.md>) | #[Linked References](<Linked References.md>) #[Book](<Book.md>) | #[Sidebar](<Sidebar.md>) | #[Tags](<Tags.md>) | #[Evergreen Notes](<Evergreen Notes.md>) | #[Block References](<Block References.md>) | #[Templates](<Templates.md>) | #[Query](<Query.md>)

## [Change Log](<Change Log.md>)
- Fixed bug that caused Roam to crash when [Query](<Query.md>)

- [Query](<Query.md>)

- [Query](<Query.md>)

- You can now show/hide paths of blocks in [Query](<Query.md>)

- Made [Query](<Query.md>)

## [Date picker](<Date picker.md>)
#[Date picker](<Date picker.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Tags](<Tags.md>) | #[Filter](<Filter.md>) | #[Linked References](<Linked References.md>) | #[Query](<Query.md>)

## [Features](<Features.md>)
- ### [Query]([Query](<Query.md>))

## [Long Videos](<Long Videos.md>)
#[roam/css](<roam/css.md>) | #[Extensions](<Extensions.md>) | #[roam/js](<roam/js.md>) | #[Sidebar](<Sidebar.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>)

- #[Daily Notes](<Daily Notes.md>) | #[Bidirectional linking](<Bidirectional linking.md>) | #[Linked References](<Linked References.md>) #[Book](<Book.md>) | #[Sidebar](<Sidebar.md>) | #[Tags](<Tags.md>) | #[Evergreen Notes](<Evergreen Notes.md>) | #[Block References](<Block References.md>) | #[Templates](<Templates.md>) | #[Query](<Query.md>)

## [Meeting notes](<Meeting notes.md>)
#[Page References](<Page References.md>) | #[Daily Notes](<Daily Notes.md>) | #[Date picker](<Date picker.md>) | #[Linked References](<Linked References.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Filter](<Filter.md>) | #[Query](<Query.md>)

#[Current time](<Current time.md>) | #[Page References](<Page References.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Linked References](<Linked References.md>) | #[Query](<Query.md>)

## [Project Management](<Project Management.md>)
#[Page References](<Page References.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>)

- #[Page References](<Page References.md>) | #[Query](<Query.md>)

## [Research](<Research.md>)
#[Query](<Query.md>)

- #[Query](<Query.md>)

## [September 27th, 2021](<September 27th, 2021.md>)
- Fixed bug that caused Roam to crash when [Query](<Query.md>)

## [TODO/DONE](<TODO/DONE.md>)
#[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>)

#[roam/css](<roam/css.md>) | #[Extensions](<Extensions.md>) | #[roam/js](<roam/js.md>) | #[Sidebar](<Sidebar.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>)

- #[Daily Notes](<Daily Notes.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Page References](<Page References.md>) | #[Query](<Query.md>)

## [Task Management](<Task Management.md>)
#[Current time](<Current time.md>) | #[Query](<Query.md>)

#[Query](<Query.md>)

#[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>)

- #[Daily Notes](<Daily Notes.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Page References](<Page References.md>) | #[Query](<Query.md>)

## [Today](<Today.md>)
- The "today" function auto generates today's daily notes page, it will either give you a static result, or a variable result ("today" will always point to today's date, rather than a set date) when used in a [Query](<Query.md>)

## [Tomorrow](<Tomorrow.md>)
- The "tomorrow" function auto generates tomorrow's daily notes page, it will either give you a static result, or a variable result ("tomorrow" will always point to tomorrow's date, rather than a set date) when used in a [Query](<Query.md>)

## [Zettelkasten](<Zettelkasten.md>)
#[Page References](<Page References.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Query](<Query.md>)

#[Current time](<Current time.md>) | #[Page References](<Page References.md>) | #[Block References](<Block References.md>) | #[Indentation](<Indentation.md>) | #[Daily Notes](<Daily Notes.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Block Embed](<Block Embed.md>) | #[Alias](<Alias.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Indentation](<Indentation.md>) | #[Query](<Query.md>)

## [queries](<queries.md>)
- See [Query](<Query.md>)

## [roam/templates](<roam/templates.md>)
- #[Attributes](<Attributes.md>) | #[Query](<Query.md>)

