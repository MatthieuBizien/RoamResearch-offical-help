- The "today" function auto generates today's daily notes page, it will either give you a static result, or a variable result ("today" will always point to today's date, rather than a set date) when used in a [[Query]] 
    - For example, a static result: today is [[March 8th, 2021]]
    - A variable result: {{[[query]]: {and: [[today]] [[tomorrow]] {not: [[query]]}}}}
- Key Commands::
    - `/today`
