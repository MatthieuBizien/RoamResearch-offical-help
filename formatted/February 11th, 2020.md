- This week [Calendar View](<Calendar View.md>) {{table}}
    - Sun
        - Mon
            - Tues
                - Wed
                    - Thur
                        - Fri
                            - Sat
    - {{query: {and: [February 9th, 2020](<February 9th, 2020.md>)}}}
        - {{query: {and: [February 10th, 2020](<February 10th, 2020.md>)}}}
            - {{query: {and: [February 11th, 2020](<February 11th, 2020.md>)}}}
                - {{query: {and: [February 12th, 2020](<February 12th, 2020.md>)}}}
                    - {{query: {and: [February 13th, 2020](<February 13th, 2020.md>)}}}
                        - {{query: {and: [February 14th, 2020](<February 14th, 2020.md>)}}}
                            - {{query: {and: [February 15th, 2020](<February 15th, 2020.md>)}}}
- 
- 
- [Kanban Experiment](<Kanban Experiment.md>)
    - Round 1
        - **[Core Idea](<Core Idea.md>):**  Have a query for your todos next to the kanban board, then drag items from their original location into the board
        - {{kanban}}
            - Backlog
                - This item
            - DOING
            - DONE
        - **[Results](<Results.md>):**
            - Currently we aren't parsing the blocks in kanban -- need to do that for this to be useful.
            - also - would be good for tags + filters to respect info added to a block via its references.
        - {{query: {and: [TODO](<TODO.md>)}}}}
    - Round 2
        - ## Automated Kanban
            - {{table}}
                - **TODO** {{[query](<query.md>): {and: [TODO](<TODO.md>) [kb](<kb.md>) {not: {or: [scheduled](<scheduled.md>) [query](<query.md>)}}}}}
                    - **DOING** {{[query](<query.md>): {and: [TODO](<TODO.md>) [kb](<kb.md>) [scheduled](<scheduled.md>) {not: [query](<query.md>)}}}}
                        - **DONE** {{[query](<query.md>): {and: [DONE](<DONE.md>) [kb](<kb.md>) {not: [query](<query.md>)}}}}
        - Tasks
            - [ ] Upcoming kb item [kb](<kb.md>) [scheduled](<scheduled.md>) [April 18th, 2020](<April 18th, 2020.md>)
            - [x] do this thing tomorrow [February 12th, 2020](<February 12th, 2020.md>) [scheduled](<scheduled.md>) [kb](<kb.md>)
            - [ ] [kb](<kb.md>) do This thing is done
    - 
- [x] ptu this on the [kb](<kb.md>) 
- 
- 

# Backlinks
## [February 11th, 2020](<February 11th, 2020.md>)
- {{query: {and: [February 11th, 2020](<February 11th, 2020.md>)}

## [Priorities for Conor](<Priorities for Conor.md>)
- [x] Show off things on the calendar view [February 11th, 2020](<February 11th, 2020.md>)

- [x] User Onboarding Calls [February 11th, 2020](<February 11th, 2020.md>)

