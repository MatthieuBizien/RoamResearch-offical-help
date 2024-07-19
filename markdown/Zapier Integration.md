- Link for the official Roam Research <-> Zapier integration: https://zapier.com/apps/roam-research/integrations
- **Setup Process**
    1. Open the graph you want to access via Zapier
    2. Please make sure you have the latest version of Roam (via ... > Check for updates)
        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FweI5_7pLPu.png?alt=media&token=21bf5ce3-5e7c-465e-a09b-febed83acc65)
    3. Get API Token (linked elsewhere)
        1. Open your settings via ... > Settings, then go to the "Graph" tab
            -  ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FfagWR_XbE7.png?alt=media&token=0d1d5156-d91b-4078-ad2f-e35db1ceb8ba)
        2. In the "Graph" tab in settings, click on the green "+ New API Token" button
            - Do note that you need to be the owner/admin of the graph in order to create API tokens
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FvLvpJCRi36.png?alt=media&token=7cc08bb8-f684-4537-ba15-0f76c07e30d1)
        3. After clicking the button, please enter a clear description of expected usage. In the access scope, select **read & edit access** for unencrypted graphs and **append-only access** for encrypted graphs. More regarding scope below
            - More details regarding scopes for API tokens below:
                - **read-only access**
                    - (only available for unencrypted graphs)
                    - This scope only allows access to read to your graph.
                    - In the case of the Zapier integration, this means that you can only use the "Trigger"s, but not the "Action"s
                - **read & edit access**
                    - (only available for unencrypted graphs)
                    - this scope is the most permissive one. It allows the service to both read your graph and edit/add stuff to it. 
                    - In the case of the Zapier integration, this means that you can use both the "Trigger"s and the "Action"s
                - **append-only access**
                    - (available for **both** encrypted & unencrypted graphs)
                    - this access only provides the service ability to __add__ stuff to your graph
                    - In the case of the Zapier integration, this means that you can only use the "Actions"s, but not the "Trigger"s
        4. In the next screen, click on the "Clipboard" icon 📋 to copy the token to your clipboard. It will start with "roam-graph-token-"
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FtnYMdlay_y.png?alt=media&token=e49cdfbc-872e-44b6-bc01-4b0c0b22a386)
    4. Then you can use the credentials to connect your Roam graph to Zapier!
    5. TODO: Better documentation
