- [Hiring](<Hiring.md>) [Work at Roam](<Work at Roam.md>) [Clojure Engineer](<Clojure Engineer.md>) - [Backend Role](<Backend Role.md>) [Take Home Project](<Take Home Project.md>)
    - [ ] Given a map, or a [datascript](https://github.com/tonsky/datascript) database at two points in time
    - [ ] Generate a diff of the two structures
    - [ ] Generate the minimal transaction which will bring A -> B, and vice versa.
    - [Bonus](<Bonus.md>) 
        - [ ] Given a set of User-Events which map to certain transactions - find the sequence of user events which brought A -> B, or which would bring B -> A
        - [ ] Take a roam outline tree, and create a datascript DB with just the data contained within it  - such as this one "This item"
        - [ ] Publish your code and the demo on a roam graph using `roam/render` and custom components
            - Roam allows you to write arbitrary CLJS code - and evaluate it in your graph - you can use this code - and the roam Alpha API to query your graph, and create mutations for it.
            - Submit your answer as a roam-graph
            - All code should be in the same Roam Graph as the working demo.
            - {{[roam/render](<roam/render.md>): ((uP_2barEP)) ((cpgzSMTye))}}
                - ```clojure
(ns starting-point-for-custom-roam
  (:require
   [reagent.core :as r]
   [datascript.core :as d]
   [roam.datascript.reactive :as dr]))

(defn x [{b :block-uid} x]
  	[:div.bp3-card 
     [:ul
     [:li (pr-str @(dr/pull '[:block/string {:block/children ...}
                              :block/uid 
                              ] x))]
      [:li [:h3"Schema" ]
       (pr-str @(dr/q 
                     '[:find [?a ...]
                       :where [_ ?a _]]))]
     [:li (pr-str (keys @(dr/pull '[*] [:block/uid b])))]]]
  )```
            - This item
                - Has children
                    - A
                    - B
                    - C
        - ## IF you want to also be considered for  #[UI Engineer](<UI Engineer.md>)
            - [ ] generate a UI for displaying the diff 
            - [ ] create a simple component that will let you save the state of a block subtree at various points, and return to these states - by firing new transactions
- Import
    - [December 1st, 2020](<December 1st, 2020.md>)
        - From: December 1st, 2020.json

# Backlinks
## [Roam Change Log](<Roam Change Log.md>)
- [February 8th, 2021](<February 8th, 2021.md>)

