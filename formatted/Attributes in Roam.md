- **[status](<status.md>):** [Experimental](<Experimental.md>)
    - ## Warning: This feature is in alpha, hasn't been fully developed yet.  This is mostly for experimentation
- Blocks and Pages in Roam can both have attributes
    - **[attributes are formed by wring `](<attributes are formed by wring `.md>):**` at the front of a block
        - **[see "founder of](<see "founder of.md>):** [Roam](<Roam.md>)"
    - The structure of an attribute is `Entity Attribute Value`
- When an attribute is at the first level of indentation of a page, it is attached to the page itself
    - **[see "status](<see "status.md>):** [Experimental](<Experimental.md>)"
- When the block which an attribute is attached to only contains references to other blocks or pages, (or commas or the word and) the attribute is attached to those referenced entities instead
    - ## Example
        - [Conor](<Conor.md>) and [Josh](<Josh.md>)
            - **[founder of](<founder of.md>):** [Roam](<Roam.md>)
            - **[Programming Languages](<Programming Languages.md>):** [Clojure](<Clojure.md>) [Javascript](<Javascript.md>)  
        - This setup will create 6 EAV relationships
            - Conor - founder of - Roam
            - Josh -  founder of - Roam
            - Conor - Programming Languages - Clojure 
            - Conor - Programming Languages - Javascript
            - Josh  - Programming Languages - Clojure
            - Josh - Programming Languages - Javascript
- When the block that an attribute is defined on contains only a string, then the value of the string is assigned as the value of the attribute
    - ## Examples
        - [Conor](<Conor.md>)
            - **[founder of](<founder of.md>):** [Localocracy](<Localocracy.md>)
            - **[age](<age.md>):** 32
        - [Josh](<Josh.md>)
            - **[age](<age.md>):** 22
- 
- These attributes will eventually have a lot more power in Roam, for now, the only thing they are used for is to generate tables
    - and charts in the limited case of attributes with numerical values that are excuslively placed on Daily Note pages 
- Attribute tables are written as 
    - `{{attr-table:` `[``Link to attribute``](<``Link to attribute``.md>)``}}` 
    - Example
        - {{attr-table: [status](<status.md>)}}
- Attribute tables are "greedy" -- and try to pull in all related attributes that could be relevant to the table
    - Steps
        - They look at the page listed to see if and where  it has been used as an attribute
        - they will look for all of the entities which have the attribute assigned
        - they will then find all of the other attributes which have been associated with those entities, and chart the values of each of those subsequent attributes
    - Example
        - Attribute Table for Age  
            - ## {{attr-table: [age](<age.md>)}} 
                - Includes more info than just age
        - ## Attribute Table for Programming Languages {{attr-table: [Programming Languages](<Programming Languages.md>)}}
            - includes more info than just programming languages
- Clicking on the cell of each table will bring you to the place where the attribute was defined
    - The attributes do not need to be all defined in one place to be collected into the table
        - For example, if you click on [San Francisco](<San Francisco.md>) in either of the above tables, you'll see that the **lives in** relationship was defined on the [Conor](<Conor.md>) page, not near where other attributes were defined. 
- Attributes can themselves be annotated using an [Associative Data Model](<Associative Data Model.md>)
- 

# Backlinks
## [December 2nd, 2019](<December 2nd, 2019.md>)
- Probably best to replace this with [Attributes in Roam](<Attributes in Roam.md>)

## [Example Routine](<Example Routine.md>)
- The advantage of using [Bidirectional Links](<Bidirectional Links.md>) or [Attributes in Roam](<Attributes in Roam.md>)

## [January 5th, 2020](<January 5th, 2020.md>)
- Is it stored in something like [Attributes in Roam](<Attributes in Roam.md>)?

- # [Tables](<Tables.md>) and [Attributes in Roam](<Attributes in Roam.md>)

## [July 22nd, 2020](<July 22nd, 2020.md>)
- [Attributes in Roam](<Attributes in Roam.md>)

## [March 16th, 2020](<March 16th, 2020.md>)
- Collection of 9 [Attributes in Roam](<Attributes in Roam.md>)

