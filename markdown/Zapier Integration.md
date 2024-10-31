- [Zapier](https://zapier.com/apps/roam-research/integrations) lets you connect Roam Research to 6,000+ other web services. Automated connections called Zaps, set up in minutes with no coding, can automate your day-to-day tasks and build workflows between apps that otherwise wouldn't be possible.
- Link: https://zapier.com/apps/roam-research/integrations
- ### **Getting Started**
    - **Walkthrough Video** showing how to connect your Roam graph to Zapier
        - {{[[video]]: https://www.loom.com/share/0434049965254f3e86ae8909a368ca52}}
        - apart from the setup process, this video also demonstrates how to use Zap templates, in particular, [one that adds new starred emails in Gmail to Roam daily note page](https://zapier.com/apps/gmail/integrations/roam-research/255568759/add-new-starred-emails-in-gmail-to-your-daily-note-pages-in-roam-research)
    - Steps::
        1. Open the graph you want to link with Zapier
        2. Create a new API Token
            - {{embed-children: ((te_tiD1jQ))}}
        3. Then setting up the graph in Zapier:
            - **Walkthrough GIF**
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2Fn6-ucfieHt.gif?alt=media&token=d0a1c875-e76c-493f-a070-484d648a3372)
            - **Steps** (if you prefer following text instead)
                1. (First of all, you need a Zapier account)
                2. Go to https://zapier.com/apps/roam-research/integrations
                3. Click on "Connect Roam Research to 6000+ apps" button
                4. In the zap that opens, click on the "Sign In" button in the "Account" section in the right sidebar
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FlHPogGN6D_.png?alt=media&token=d10531d7-f19e-423a-b55a-a260573ac29a)
                5. A popup window will then appear. There you have to enter three things: the name of your graph, whether it is encrypted or not, and the API token you got from [the previous step](((GRtcyAgHh))). 
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FUQUYqJcb0R.png?alt=media&token=2c814c19-6e81-4f62-bde0-f75ed51cbacd)
                6. You can now disregard the zap and start instead from one of our zap templates: https://zapier.com/apps/roam-research/integrations#zap-template-list 
- Details
    - **More info on Zapier terminology, and what Roam building blocks you can use**
        - Each Zap has one app as the **Trigger**, where your information comes from and which causes one or more **Actions** in other apps, where your data gets sent automatically.
        - For now, the Roam Zapier Integration has **2 triggers**, **3 write actions** and **1 search action**
            - **2 triggers**
                1. New Linked Reference for a Page/Block
                2. New or modified Linked Reference for a Page/Block
            - **3 write actions**
                1. Add Content to a Daily Note Page
                2. Add Content to a Page
                3. Add Content underneath an existing Block in Your Graph
            - **1 search action**
                1. Get Data for a Page / Block
        - If you're using an **unencrypted graph**, you can use all of the building blocks above
        - If you're using an **encrypted graph**, you cannot do any reads from the graph (due to it being end to end encrypted), so the only primitives you can use are the **3 write actions**
            - In other words, you can only append/add stuff to the graph. This is also suggested by the fact that the only kind of API tokens you can create for encrypted graphs is **append-only access**
