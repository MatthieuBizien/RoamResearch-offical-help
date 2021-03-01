- Mermaid is a markdown language for drawing diagrams based on text
- This component will interpret all of the text indented underneath it - and - if it is formatted correctly, will render a mermaid diagram
- Note -- it does not play nicely with other features of Roam -- like [Block References](<Block References.md>) or [Bidirectional Links](<Bidirectional Links.md>) - if you want to have the elements of you diagram be links you can click - or to include images or other richly formatted blocks - use the native Roam [Diagrams](<Diagrams.md>) which are also more **point and click interactive**
- **[Documentation](<Documentation.md>):** https://mermaid-js.github.io/mermaid/#/
- Styling for [Roamcult Themes](<Roamcult Themes.md>) https://mermaid-js.github.io/mermaid/#/classDiagram?id=styling
- 
- https://mermaid-js.github.io/mermaid-live-editor
- How to use
    - type `{{``mermaid}}`
        - Text goes
        - Here
- **[Examples](<Examples.md>):**
    - {{mermaid}}
        - erDiagram
        CUSTOMER }|..|{ DELIVERY-ADDRESS : has
        CUSTOMER ||--o{ ORDER : places
        CUSTOMER ||--o{ INVOICE : "liable for"
        DELIVERY-ADDRESS ||--o{ ORDER : receives
        INVOICE ||--|{ ORDER : covers
        ORDER ||--|{ ORDER-ITEM : includes
        PRODUCT-CATEGORY ||--|{ PRODUCT : contains
        PRODUCT ||--o{ ORDER-ITEM : "ordered in"
					
    - {{mermaid}}
        - graph TD

            - A[Christmas] -->|Get money| B(Go shopping)
            - B --> C{Let me think}
            - C -->|One| D[Laptop]
            - C -->|Two| E[iPhone]
            - C -->|Three| F[fa:fa-car Car]
					
    - [Gantt Charts](<Gantt Charts.md>)
        - {{mermaid}}
            - gantt
	title A Gantt Diagram
	dateFormat  YYYY-MM-DD
	section Section
	A task           :a1, 2014-01-01, 30d
	Another task     :after a1  , 20d
	section Another
	Task in sec      :2014-01-12  , 12d
        - **[Documentation](<Documentation.md>):** https://mermaid-js.github.io/mermaid/#/gantt
        - 
    - {{mermaid}}
        - stateDiagram
	[*] --> Still
	Still --> [*]

	Still --> Moving
	Moving --> Still
	Moving --> Crash
	Crash --> [*]
					
    - {{mermaid}}
        - pie title Pets adopted by volunteers
            - "Dogs" : 386
            - "Cats" : 85
            - "Rats" : 15					
- 

# Backlinks
## [Roam Change Log](<Roam Change Log.md>)
- #[Hidden Features](<Hidden Features.md>) [Mermaid Diagrams](<Mermaid Diagrams.md>)

