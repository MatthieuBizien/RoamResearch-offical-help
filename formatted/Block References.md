- One of Roam's most powerful, flagship features
- What is it?
    - Every block in Roam has its own ID, unique to only that block
        - When you want to refer to something, instead of copying the literal content of that block, you can copy the ID that refers to that block  
    - Like every page can have linkage with each other, blocks can be interconnected too
- Why is it important?
    - Block references help you make every block of your notes more reusable, either by yourself in the future, or by others when the graph is shared
    - This means 
        - Less reinvention of the wheel
            - No need to copy and paste, and generate a bunch of content that means the same thing!
        - Less maintenance, less confusion
            - If you change the content in the original block, the references that point towards the original block will all be automatically changed, saving you time to maintain multiple copies of the same content
        - More incentives for quality content creation
            - The more insightful content, the more it gets referenced by yourself and others 
        - Ultimately, knowledge is no longer static, but becomes fluid
            - You are free to open up different windows in the sidebar, Roam around and remix and rematch content from articles, people, days, and projects
- How to use it?
    - You can replace block references with text, embed, alias, original or with text + alias.  The most important of these is [text and alias](((7Zv5Vm1fO)))
        - **[Example](<Example.md>):**
            - from [Beating the Averages](<Beating the Averages.md>)
                - This is a block ref
                    - In the summer of 1995, my friend Robert Morris and I started a startup called [Viaweb](http://docs.yahoo.com/docs/pr/release184.html). Our plan was to write software that would let end users build online stores. What was novel about this software, at the time, was that it ran on our server, using ordinary Web pages as the interface.
                        - It is a window onto a block from somewhere else in your Roam Graph - changes to that block will be reflected here as well. 
                - If you click on this you will now see this menu
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FMXJp9DtIl0.png?alt=media&token=e32c1861-66ae-4c8e-8709-142824b10ba4)
                - [Jump to block](<Jump to block.md>) and [open in sidebar](<open in sidebar.md>) will do the same thing that clicking and shift-clicking (respectively) used to - they move either the focus of your main work area to that block - or open it in it's original context
                    - You can also do these operations with Control-o and Control-shift-o (o standing for open) respectively. 
                - If you select [Replace With](<Replace With.md>) you will see this menu
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FANYfuprm6c.png?alt=media&token=109625d3-b64b-4beb-891a-4a070a7037dc)
                - If you choose to replace with `embed` you will get this:
                    - In the summer of 1995, my friend Robert Morris and I started a startup called [Viaweb](http://docs.yahoo.com/docs/pr/release184.html). Our plan was to write software that would let end users build online stores. What was novel about this software, at the time, was that it ran on our server, using ordinary Web pages as the interface.
                        - You can now see the refs in the right margin and the block now lives here and its original location is now holding a reference to the above block
                        - This is useful when you want to change the location of a block to make the references more easily accessible or where the original block makes more sense to be 
                        - This essentially gives you a portal to the original source material - if you edit text within the embed - it will change all the references
                - If you choose to replace with `original` you will get this:
                    - In the summer of 1995, my friend Robert Morris and I started a startup called [Viaweb](http://docs.yahoo.com/docs/pr/release184.html). Our plan was to write software that would let end users build online stores. What was novel about this software, at the time, was that it ran on our server, using ordinary Web pages as the interface.
                        - You can now see the refs in the right margin and the block now lives here and its original location is now holding a reference to the above block
                        - This is useful when you want to change the location of a block to make the references more easily accessible or where the original block makes more sense to be 
                - If you choose to replace with `text` you will get this:
                    - In the summer of 1995, my friend Robert Morris and I started a startup called [Viaweb](http://docs.yahoo.com/docs/pr/release184.html). Our plan was to write software that would let end users build online stores. What was novel about this software, at the time, was that it ran on our server, using ordinary Web pages as the interface.
                        - It is the same as copy-pasting the original text - there is no longer any connection between the text and the new block
                - If you choose to replace with `alias` you will get this:
                    - [*](((0EEP-FcAj)))
                        - This gives you a link to the original item - but in a hyperlinked alias
                            - The format for aliases is `[alias](((blockid))``)`
                                - We default to having the alias as the `*` footnote symbol, but you can edit this however you feel
                            - This is useful if you want to point to multiple ideas, but refer to them with another phrasing - like [Premise 1](((0EEP-FcAj))) and [Premise 2](((-FdvpO3U0)))
                                - you will see that if you hover over an alias you can see the text of the block you are pointing to as a preview
                - If you choose to replace with [text and alias](<text and alias.md>) you will get this:
                    - In the summer of 1995, my friend Robert Morris and I started a startup called [Viaweb](http://docs.yahoo.com/docs/pr/release184.html). Our plan was to write software that would let end users build online stores. What was novel about this software, at the time, was that it ran on our server, using ordinary Web pages as the interface. [*](((0EEP-FcAj)))
                        - This is useful for drafting - or making a modified version of the original text - you have an alias pointing to the source material - but the text is conveniently there for editing/rewording etc. [Writing](<Writing.md>)
    - Apply children
        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FAwRs4Xe2HD.gif?alt=media&token=690c1f18-49e3-44b1-ad9a-065907adbf1d)
    - Copying multiple block references
        - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FR4UsRcsCSC.gif?alt=media&token=6cdb2595-8c9a-4488-ab8e-f6e2be187243)
- **[Team GIFs](<Team GIFs.md>):**
    - Creating a block reference
        - right click
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2F4zqz_5nSei.gif?alt=media&token=c6dd3cc3-a473-4f36-8f01-4e59bf436f6b)
        - alt-drag and drop
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FADFwTPg2pM.gif?alt=media&token=b3613a5a-d682-49df-9bf3-0c19a4ac434e)
    - Replace with 
        - text and alias
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FBWDX1PveeB.gif?alt=media&token=b794a690-b9ec-4583-99e6-388e751c8b9f)
        - text
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FSEpS8MIonj.gif?alt=media&token=0e2f8fa2-329f-4968-8d50-698a6c2e9ecf)
        - original
            - no children
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FrzGMUmmntb.gif?alt=media&token=9edf69cb-e4b7-49cb-8e76-2e9533801d95)
            - with children
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FAwRs4Xe2HD.gif?alt=media&token=690c1f18-49e3-44b1-ad9a-065907adbf1d)
    - Apply children
        - as text
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FZLu6Q6rxwj.gif?alt=media&token=cc1fb2b3-1870-4ebc-a861-e8be9ef332d5)
        - as references
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FpY2NwzY6BD.gif?alt=media&token=3e7ac862-c136-4b30-afc4-8c0227014b2a)
    - Inline references
        - Toggling and navigating
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FZ5kZT9R7GZ.gif?alt=media&token=ebe87c96-58e9-4819-b800-c09e0eac3b54)
            - 
        - Read status
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp-documentation%2FOUwTJ-sF7-.gif?alt=media&token=ac39057d-d4a0-4f3b-aa83-4074c645b9d9)
- **[Community Videos](<Community Videos.md>):**
    - Quick Intro to Block References in Roam Research by [Matias Faure](<Matias Faure.md>)
        - {{[video](<video.md>): https://www.youtube.com/watch?v=O413tVCseio}}
#[Block References](<Block References.md>) | #[Right Sidebar](<Right Sidebar.md>)
    - Roam Research: Quick access to concepts/definitions using Links and Block References by [Les Kristofs](<Les Kristofs.md>)
        - {{[video](<video.md>): https://www.youtube.com/watch?v=nhGhg0LdgSQ}}
#[Linked References](<Linked References.md>) | #[Block References](<Block References.md>)
- **[Articles](<Articles.md>):**
    - [Roam’s Block Reference Context Menu: A Primer](https://roamstack.com/roam-block-reference-menu/) by [RoamStack](<RoamStack.md>)
        - #[Block References](<Block References.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Block Embed](<Block Embed.md>) | #[text and alias](<text and alias.md>) | #[Alias](<Alias.md>) 
    - [What is a block in Roam Research (and what are block embeds)?](https://www.roamtips.com/home/what-is-block-roam-research) by [Roam Tips](<Roam Tips.md>)
- **[Key Commands](<Key Commands.md>):**
    - `(())`

# Backlinks
## [ Commands](< Commands.md>)
- [Block References](<Block References.md>)

## [Audio Player](<Audio Player.md>)
#[Audio Player](<Audio Player.md>) | #[Block References](<Block References.md>)

## [Beginner's Guide](<Beginner's Guide.md>)
- #[Daily Notes](<Daily Notes.md>) | #[Bidirectional linking](<Bidirectional linking.md>) | #[Linked References](<Linked References.md>) #[Book](<Book.md>) | #[Sidebar](<Sidebar.md>) | #[Tags](<Tags.md>) | #[Evergreen Notes](<Evergreen Notes.md>) | #[Block References](<Block References.md>)

## [Block References](<Block References.md>)
#[Block References](<Block References.md>)

#[Linked References](<Linked References.md>) | #[Block References](<Block References.md>)

- #[Block References](<Block References.md>)

## [Blocks](<Blocks.md>)
- One of Roam's most powerful features is [Block References](<Block References.md>).

#[Blocks](<Blocks.md>) | #[Block References](<Block References.md>)

#[Blocks](<Blocks.md>) | #[Block References](<Block References.md>)

## [Chinese](<Chinese.md>)
#[Page References](<Page References.md>) | #[Bidirectional linking](<Bidirectional linking.md>) | #[Block References](<Block References.md>)

## [Current time](<Current time.md>)
#[TODO/DONE](<TODO/DONE.md>) | #[Daily Notes](<Daily Notes.md>) | #[Filter](<Filter.md>) | #[Linked References](<Linked References.md>) | #[Block Embed](<Block Embed.md>) | #[Current time](<Current time.md>) | #[Block References](<Block References.md>)

## [FAQ](<FAQ.md>)
- ### **How can I make a** [block reference]([Block References](<Block References.md>))

## [Formatting](<Formatting.md>)
- You can select [block ref]([Block References](<Block References.md>))

- You can select any text you want to use as an alias and then press `cmd+k` (macOS) / `ctrl+k` (PC) and then enter the [block ref]([Block References](<Block References.md>))

## [Journaling](<Journaling.md>)
- #[Daily Notes](<Daily Notes.md>) | #[Templates](<Templates.md>) | #[Block References](<Block References.md>)

## [Kanban](<Kanban.md>)
#[Kanban](<Kanban.md>) | #[Block References](<Block References.md>)

## [Kids](<Kids.md>)
#[Daily Notes](<Daily Notes.md>) | #[Page References](<Page References.md>) | #[Bidirectional linking](<Bidirectional linking.md>) | #[Task Management](<Task Management.md>) | #[Table](<Table.md>) | #[Current time](<Current time.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Templates](<Templates.md>) | #[Block References](<Block References.md>)

## [Korean](<Korean.md>)
- #[Right Sidebar](<Right Sidebar.md>) | #[Block References](<Block References.md>)

## [Long Videos](<Long Videos.md>)
#[Block References](<Block References.md>)

- #[Daily Notes](<Daily Notes.md>) | #[Bidirectional linking](<Bidirectional linking.md>) | #[Linked References](<Linked References.md>) #[Book](<Book.md>) | #[Sidebar](<Sidebar.md>) | #[Tags](<Tags.md>) | #[Evergreen Notes](<Evergreen Notes.md>) | #[Block References](<Block References.md>)

## [Longform writing](<Longform writing.md>)
#[Right Sidebar](<Right Sidebar.md>) | #[Block References](<Block References.md>)

- #[Tags](<Tags.md>) | #[Filter](<Filter.md>) | #[Version Control](<Version Control.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Block References](<Block References.md>)

## [Meeting notes](<Meeting notes.md>)
#[Page References](<Page References.md>) | #[Daily Notes](<Daily Notes.md>) | #[Date picker](<Date picker.md>) | #[Linked References](<Linked References.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Filter](<Filter.md>) | #[Query](<Query.md>) | #[Block References](<Block References.md>)

#[Current time](<Current time.md>) | #[Page References](<Page References.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Linked References](<Linked References.md>) | #[Query](<Query.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Block References](<Block References.md>)

## [Project Management](<Project Management.md>)
- #[Page References](<Page References.md>) | #[TODO/DONE](<TODO/DONE.md>) | #[Block References](<Block References.md>)

- #[Page References](<Page References.md>) | #[Query](<Query.md>) | #[Block References](<Block References.md>)

## [Research](<Research.md>)
#[Page References](<Page References.md>) | #[Linked References](<Linked References.md>) | #[Unlinked References](<Unlinked References.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Block References](<Block References.md>)

## [Right Sidebar](<Right Sidebar.md>)
#[Block References](<Block References.md>)

## [Roam Change Log](<Roam Change Log.md>)
- Added shortcut hint in context menu for copying [Block References](<Block References.md>)

## [Russian](<Russian.md>)
#[Page References](<Page References.md>) | #[Linked References](<Linked References.md>) | #[Graph Overview](<Graph Overview.md>) | #[Unlinked References](<Unlinked References.md>) | #[Daily Notes](<Daily Notes.md>) | #[Block References](<Block References.md>)

## [Scripture Study](<Scripture Study.md>)
#[Page References](<Page References.md>) | #[Linked References](<Linked References.md>) | #[Graph Overview](<Graph Overview.md>) | #[Block References](<Block References.md>)

- #[Graph Overview](<Graph Overview.md>) | #[Date picker](<Date picker.md>) | #[Upload Files](<Upload Files.md>) | #[Markdown](<Markdown.md>) | #[Page References](<Page References.md>) | #[Block References](<Block References.md>)

- #[Page References](<Page References.md>) | #[Linked References](<Linked References.md>) | #[Graph Overview](<Graph Overview.md>) | #[Block References](<Block References.md>)

## [Search](<Search.md>)
- # [Block References](<Block References.md>)

## [Spanish](<Spanish.md>)
#[Daily Notes](<Daily Notes.md>) | #[Page References](<Page References.md>) | #[Formatting](<Formatting.md>) | #[Graph Overview](<Graph Overview.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Linked References](<Linked References.md>) | #[Navigation](<Navigation.md>) | #[Block References](<Block References.md>)

## [Studying](<Studying.md>)
#[Page References](<Page References.md>) | #[Sidebar](<Sidebar.md>) | #[Block References](<Block References.md>)

## [TODO/DONE](<TODO/DONE.md>)
#[TODO/DONE](<TODO/DONE.md>) | #[Daily Notes](<Daily Notes.md>) | #[Filter](<Filter.md>) | #[Linked References](<Linked References.md>) | #[Block Embed](<Block Embed.md>) | #[Current time](<Current time.md>) | #[Block References](<Block References.md>)

#[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>) | #[Page References](<Page References.md>) | #[Daily Notes](<Daily Notes.md>) | #[Block References](<Block References.md>)

## [Task Management](<Task Management.md>)
#[TODO/DONE](<TODO/DONE.md>) | #[Query](<Query.md>) | #[Page References](<Page References.md>) | #[Daily Notes](<Daily Notes.md>) | #[Block References](<Block References.md>)

#[TODO/DONE](<TODO/DONE.md>) | #[Daily Notes](<Daily Notes.md>) | #[Filter](<Filter.md>) | #[Linked References](<Linked References.md>) | #[Block Embed](<Block Embed.md>) | #[Current time](<Current time.md>) | #[Block References](<Block References.md>)

## [Welcome to Roam v2](<Welcome to Roam v2.md>)
- **Organizing information is effortless with** [page]([Page References](<Page References.md>))/[block references]([Block References](<Block References.md>))

## [Wiki](<Wiki.md>)
- #[Attributes](<Attributes.md>) | #[Block References](<Block References.md>)

## [Zettelkasten](<Zettelkasten.md>)
#[Page References](<Page References.md>) | #[Right Sidebar](<Right Sidebar.md>) | #[Block References](<Block References.md>)

#[Current time](<Current time.md>) | #[Page References](<Page References.md>) | #[Block References](<Block References.md>)

- #[Block References](<Block References.md>)

- #[Page References](<Page References.md>) | #[Block References](<Block References.md>)

- #[Page References](<Page References.md>) | #[Linked References](<Linked References.md>) | #[Unlinked References](<Unlinked References.md>) | #[Indentation](<Indentation.md>) | #[Block References](<Block References.md>)

