- #.doc-mode
    - # **Types of queries**
        - ### **and**
            - Find all blocks matching multiple conditions – i.e. blocks or their parents containing multiple page or block references.
            - `{{query: {and: [[page A]] [[page B]] }}}
{{query: {and: [[articles]] ((block)) }}}
{{query: {and: [[Tyler Cowen]] ((block)) [[econ]] }}}
`
        - ### **or**
            - Find all blocks matching any of a number of conditions – i.e. blocks or their parents containing any of the selected page or block references.

            - `{{query: {or: [[page A]] [[page B]] }}}
{{query: {or: [[Zen]] [[Buddhism]] }}}
{{query: {or: [[Utah]] [[Idaho]] [[Montana]] }}}
`
        - ### **not**
            - Exclude blocks matching any of the page or block references selected.
            - `{{query: {and: [[page A]] {not: [[page B]] }}}}
{{query: {and: [[Slate Star Codex]] {not: [[psychiatry]] }}}}`
        - ### **between**
            - Finds all blocks on daily pages and blocks mentioning a date between two days. You can use the following as a shorthand: [[today]], [[tomorrow]], [[yesterday]], [[last week]], [[next week]], [[last month]], and [[next month]]. ^^Only works on Daily Notes page^^.
            - `{{query: {between: [[January 1st, 2021]] [[today]] }}
{{query: {and: [[mistakes]] {between: [[January 1st, 2020]] [[December 31st, 2020]] }}}}
{{query: {and: [[TODO]] {between: [[last week]] [[today]] }}}}`
    - ## Community Videos::
        - ### Query syntax and logic: how to ask Roam questions with queries by [[Robert Haisfield]]
            - {{[[video]]: https://www.youtube.com/watch?v=LJZBGJOzhUY&t=20s&ab_channel=RobertHaisfield}}
        - ### How Queries Work in Roam Research by [[R.J. Nestor]]
            - {{[[video]]: https://www.youtube.com/watch?v=lBmklV0n8D0}}
        - ### Roam Research Search Queries by [[David Perell]]
            - {{[[video]]: https://www.youtube.com/watch?v=HoccqyiHvPw}}
        - ### Insight Hunting with Queries in Roam by [[Cortex Futura]]
            - {{[[video]]: https://www.youtube.com/watch?v=gLAlQGM_l1Q}}
        - ### Roam Research Query Tutorial: Pending Tasks for Task Management and Task Dashboard Using Queries by [[The Upgraded Brain]]
            - {{[[video]]: https://www.youtube.com/watch?v=Kg5omIyWu8s}}
    - ## Articles::
        - ### [How to query in Roam](https://roamhacks.com/how-to-query-roam/) by [[Roamhacks]]
        - ### [Searching Roam With Queries: A Primer](https://www.roamstack.com/roam-queries-primer/) by [[RoamStack]]
    - ## Key Commands::
        - `/query`
