- [[Project: 30 Demos in 6 Weeks]]
    - {{[[DONE]]}} [[Experiment]] - Demo how it was possible to use the combination of [[roam/render]] and [[roam/templates]] to create a **factory template** the creates customizable dropdowns which add block-refs to a selected item from a particular list.
        - Video
            - {{[[video]]: https://www.loom.com/share/1adf78d01db9435fb69bf4249a296a66}}
        - To use 
            - {{[[TODO]]}} copy this block into your graph #.bp3-card
                - ## Conor's [[Factory Template]] for creating Option Dropdowns based on block refences  #[[roam/templates]]
                    - Congratulations! You have just created a new **Dropdown Template** 
                        - #.rm-g  #.rm-h 
                            - {{[[TODO]]}} Edit the block below to change the template
                                - [[RM/Component/Select]] an item from Dropdown List [[roam/templates]]
                                    - {{[[roam/render]]: ((pBiRi-Hba)) ((iYpGdGk0B))}}
                            - {{[[TODO]]}} Edit these blocks to change the items visible in the dropdown
                                - Dropdown List
                                    - A
                                    - B
                                    - C
                    - {{[[TODO]]}}  Apply the template #.rm-E 
                        - {{[[TODO]]}} type `;;`   
                        - {{[[TODO]]}} search for the label you've given it here [->](((ovqdW0R_j))) 
                        -  This will produce a custom Select Component like this one 
                            - {{[[roam/render]]: ((pBiRi-Hba)) ((iYpGdGk0B))}} 
                            - built off this  Dropdown List
                    - This component is an experiment, and was built paritally as a demo of what you can do with  [[roam/render]] - a feature of roam that allows you to build interactive components out of code blocks written __inside__ your roam graph and referenced by the component in this format `{{[[roam/render]]: ((id for the code block goes here)) }}` 
                        - If you'd like to edit the code for the template - you can edit it [here](((pBiRi-Hba)))
                            - ```clojure
                              (ns niki.dropdown
                                (:require
                                  [clojure.string :as str]
                                  [roam.block :as block]
                                  [roam.datascript.reactive :as dr]))
                              
                              (defn replace-with-block-ref [block-uid opts-uid ref-uid]
                                (let [before (->> [:block/uid block-uid]
                                               (dr/pull [:block/string])
                                               (deref)
                                               :block/string)
                                      pattern (re-pattern
                                                (str
                                                  "\\{\\{"
                                                  "(?:\\[\\[)?roam/render(?:\\]\\])?:" ;; [[roam/render]]
                                                  "\\s*"
                                                  "\\(\\(([a-zA-Z0-9-]+)\\)\\)"        ;; render code block
                                                  "\\s*"
                                                  "\\(\\((" opts-uid ")\\)\\)"         ;; options block
                                                  "\\s*"
                                                  "(\\(\\(([a-zA-Z0-9-]+)\\)\\))?"     ;; selected block
                                                  "\\}\\}"))
                                      after   (str/replace before pattern
                                                (str "{{[[roam/render]]: (($1)) (($2)) ((" ref-uid "))}}"))]
                                  (block/update
                                    {:block
                                     {:uid block-uid 
                                      :string after}})))
                              
                              (defn view-children-clickable [block-uid opts-uid selected-uid]
                                (let [children (->> [:block/uid opts-uid]
                                                 (dr/pull [{:block/children [:block/uid :block/string]}])
                                                 deref
                                                 :block/children)]
                                  [:select {:id opts-uid
                                            :on-change #(replace-with-block-ref block-uid opts-uid (-> % .-target .-value))}
                                   (for [c children]
                                     [:option
                                      {:value    (:block/uid c)
                                       :selected (= (:block/uid c) selected-uid)
                                       :on-change #(replace-with-block-ref (:block/string c))}
                                      (:block/string c)])]))
                              
                              (defn main [{:keys [block-uid]} [_ opts-uid] & [[_ selected-uid]]]
                                [view-children-clickable block-uid opts-uid selected-uid])
                              ```
