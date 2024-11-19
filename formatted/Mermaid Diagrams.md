- An embedded version of MermaidJS, create mermaid diagrams inside of Roam!
    - To read more about Mermaid syntax see https://mermaid.js.org/intro/
- To create a mermaid diagram
    - type or copy and paste`{{mermaid}}` into a new block
    - It will look like below
    - {{mermaid}}
- **[Examples](<Examples.md>):**
    - Flowchart
        - {{[mermaid](<mermaid.md>)}}
            - flowchart TB
                - A --> C
                - A --> D
                - B --> C
                - B --> D
    - Sequence Diagram
        - {{[mermaid](<mermaid.md>)}}
            - sequenceDiagram
                - Alice->>John: Hello John, how are you?
                - John-->>Alice: Great!
                - Alice-)John: See you later!
    - Gantt Chart
        - {{[mermaid](<mermaid.md>)}}
            - gantt
                  dateFormat  YYYY-MM-DD
                  title       Adding GANTT diagram functionality to mermaid
                  excludes    weekends
                  %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)
              
                  section A section
                  Completed task            :done,    des1, 2014-01-06,2014-01-08
                  Active task               :active,  des2, 2014-01-09, 3d
                  Future task               :         des3, after des2, 5d
                  Future task2              :         des4, after des3, 5d
              
                  section Critical tasks
                  Completed task in the critical line :crit, done, 2014-01-06,24h
                  Implement parser and jison          :crit, done, after des1, 2d
                  Create tests for parser             :crit, active, 3d
                  Future task in critical line        :crit, 5d
                  Create tests for renderer           :2d
                  Add to mermaid                      :until isadded
                  Functionality added                 :milestone, isadded, 2014-01-25, 0d
              
                  section Documentation
                  Describe gantt syntax               :active, a1, after des1, 3d
                  Add gantt diagram to demo page      :after a1  , 20h
                  Add another diagram to demo page    :doc1, after a1  , 48h
              
                  section Last section
                  Describe gantt syntax               :after doc1, 3d
                  Add gantt diagram to demo page      :20h
                  Add another diagram to demo page    :48h
- **[Roam Team Videos](<Roam Team Videos.md>):**
    - Mermaid diagrams combined with version control in Roam Research by [Conor White-Sullivan](<Conor White-Sullivan.md>)
        - {{[video](<video.md>): https://www.youtube.com/watch?v=UF22iK8fX-A&t}}
          #[Version Control](<Version Control.md>) | #[Diagram](<Diagram.md>)

# Backlinks
## [Diagram](<Diagram.md>)
- Also see [Mermaid Diagrams](<Mermaid Diagrams.md>)

