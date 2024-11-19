- If you're a developer who'd like to build extensions for Roam or connect stuff to Roam, please checkout our `developer-documentation` graph: https://roamresearch.com/#/app/developer-documentation
    - **Some starting points**
        1. [[Roam Alpha API]]: https://roamresearch.com/#/app/developer-documentation/page/tIaOPdXCj
            - This is the API that frontend Roam extensions use
                - If you're writing a [[Roam Depot]] [extension]([[Roam Depot Extensions]]), in addition to the `roamAlphaAPI`, you can also use the `extensionAPI` ([linked here](https://roamresearch.com/#/app/developer-documentation/page/y31lhjIqU))
        2. [[Roam Backend API]]: https://roamresearch.com/#/app/developer-documentation/page/W4Po8pcHQ
            - A REST API for your roam graph
            - You can use this API to read or write to your Roam graph via your own code or a variety of services
            - Some examples of things that use the Roam Backend API
                1. **[Speak to Roam]([[Apple Shortcuts/Speak to Roam]])** Apple Shortcut (speak and send transcript to your Roam graph)
                    - An Apple Shortcut which allows you to speak and send the transcript to your Roam graph (works on iPhone, iPad, Mac and even on an Apple Watch )
                        - And it’s free! (though you do have to enter an OpenAI key 😅)
                    - Latest version: **v1.2.0: ** https://www.icloud.com/shortcuts/9280597747c543eab39dd65d4aebd992
                        - Features
                            - Uses the [[OpenAI]] Whisper API to transcribe a voice recording
                            - Optionally post-process the transcript via an [[OpenAI]] GPT4 API call (prompt is customizable)
                            - If recording has been made and then something fails, then save the recording to “iCloud Drive/Shortcuts/SpeakToRoam/FailedRecordings/” folder and show a proper error message to the user
                        - [[Loom video]]s
                            - (these are for an older version but should be generally correct)
                            - The demo video: https://www.loom.com/share/76ebb8a30b1043b3a566f4077054ea73Longer 
                            - Set up guide video: https://www.loom.com/share/9bdbf2495e1f4a049d3d7354594a9808
                2. the [[Raycast]] extension
                    - ### New and Updated [[Raycast]] extension for Roam!!
                        - MacOS users, watch the demo video below to get a sense of the power of having your Roam graph (or graphs 😉) at your fingertips:
                            - {{[[video]]: https://www.loom.com/share/3fa11c532cb44822a047caecc638e47f}}
                        - Features::
                            1. Search across all your installed graphs or in one specific graph
                                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FtIlPw_oQ-a.png?alt=media&token=3c666344-8de3-4595-8947-55a216095a2e)
                                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2Fv3emRcKcRu.png?alt=media&token=59421ab9-6b29-4b13-b3ee-10ca03ed503d)
                            2. Quick capture notes to your Roam graph without leaving your keyboard
                                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2Fj8GEmEGAx8.png?alt=media&token=f65dc849-dfa1-4ce3-b820-659036a49151)
                            3. View a random block from your roam graph
                            4. Easily create Raycast quicklinks to open Roam graphs or specific pages in the graph even faster
                               ... and more features baking in the oven!
                        - Getting Started Guide
                            1. Install [[Raycast]] from https://raycast.com
                            2. Then install the Roam Extension from: https://raycast.com/roamresearch/roam-research
                            3. Follow the loom video below to add a graph
                                - {{[[video]]: https://www.loom.com/share/31ada35f7c8b4f44a2ba537b15237854}}
                        - If you run into any issues, drop us a message at support@roamresearch.com or via Intercom and we will get on it immediately.  
                        - Big thanks to [[hyc]] for their work on the initial version of this extension 🙏
                        - P.S. Users of the older versions of the Raycast extension will need to add their graph(s) again. Sorry for the inconvenience, this should only be a one time thing
        3. [[Roam Append API]]: https://roamresearch.com/#/app/developer-documentation/page/eb8OVhaFC
            - difference from the Backend API is that this can be used by [[Encrypted Graphs]] too
            - Other convenience features for writes/captures
