- Basic Setup - and the templates to help you that you can copy over from help db
    - {{[video](<../video.md>): https://www.loom.com/share/19d190d5a1054669bf681e50d09e6b0d}}
    - **[Steps](<../Steps.md>):**
        - Hello World
            - [roam/render](<../roam/render.md>) Hello World #[roam/templates](<../roam/templates.md>)
                - {{roam/render: ((7kVYGbMR2))}} 
                    - ```clojure
(defn my-component []
  [:h1 {:on-click #(js/alert "Hello World")} "Hello World"]
  )```
        - Counter with a local variable
            - [roam/render](<../roam/render.md>) Namespaces and useful functions #[roam/templates](<../roam/templates.md>)
                - {{roam/render: ((l0AwfXNWX))}} 
                    - ```clojure
(ns starting-point-for-custom-roam
  (:require
   [reagent.core :as r]
   [datascript.core :as d]
   [roam.datascript.reactive :as dr]))```
                    - ```clojure
(defn counter [_]
  (let [*count (r/atom 1)]
    (fn [_]
      [:button
       {:draggable true
        :on-click (fn [evt] (swap! *count inc))}
       @*count])))```
        - # Accessing Roam Data 
            - {{[video](<../video.md>): https://www.loom.com/share/5f243343174f4782add9b5e07ca155bd}}
            - [roam/render](<../roam/render.md>) Input + Reactive Datascript Query [roam/templates](<../roam/templates.md>)
                - {{roam/render: ((kWQSWD-zX))}}
                    - ```clojure
(ns starting-point-for-custom-roam
  (:require
   [reagent.core :as r]
   [datascript.core :as d]
   [roam.datascript.reactive :as dr]))```
                    - ```clojure



(defn text-input [x]
   [:div 	
   [:input {:value @x
              :on-change 
      (fn [e] 
         (reset! x (.. e -target -value)))}]
             ]
          )
```
                    - ```clojure
(defn query-off-string [x]
  (let [y (dr/q '[:find ?x ?title ?s
                  :in $ ?title-string
                  :where 
                  [?e :node/title ?title]
                  [(clojure.string/includes? ?title  ?title-string)]
                  [?x :block/refs ?e]
                  [?x :block/string ?s]
                  
                  ]
                @x
                )]
    [:div (pr-str (take 10 @y))]
  ))```
                    - ```clojure
(defn counter [_]
  (let [*count (r/atom 1)
        x (r/atom "TODO")]
    (fn [_]
      [:div 
       [text-input x]
       [query-off-string x]
       (pr-str @x)
      [:button
       {:draggable true
        :on-click (fn [evt] (swap! *count inc))}
       @*count]])))```
