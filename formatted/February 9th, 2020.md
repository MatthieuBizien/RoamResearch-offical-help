- ## Demoing [Encryption](<Encryption.md>) #[New Features](<New Features.md>) 
    - Encrypted blocks are now live on Roam
        - To use them type `{{``encrypt}}`
        - **[Example](<Example.md>):** {{encrypt:U2FsdGVkX19IGq42nYT82SQysswn/KYSMDPTJFTe/OV3lmF0BBO1MRb54tBZFZAr}} 
            - Then choose a hint and passphrase for that block
                - The passphrase for this [block](((RsNzjvI5f))) is `test` 
            - clicking the lock - or the text area will show you what the sting looks like when sent to us
            - only the hint is stored with Roam - the passphrase never goes to our servers
            - # WARNING
                - if you edit the text of the encrypted string - you will likely lose all of the data (only edit it when it is decrypted)
- Markdown links can be used as aliases for [Block References](<Block References.md>) and [Bidirectional Links](<Bidirectional Links.md>) #[New Features](<New Features.md>) 
    - All Men are Mortal
    - Socrates is Mortal
    - If [x](((DjhGC4Ppy))) then [y](((YdZn32tkw))) 
        - refresh your page if you don't see this ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fv8%2Fhelp%2FAIEro4drl0?alt=media&token=91e6c400-e244-4e16-8c3c-aff180ffb19b)
    - Example with aliases for pages
        -  I have a page for [Writers](<Writers.md>)
        - and I want to talk about how 
            - [Paul Graham](<Paul Graham.md>) [wrote]([Writers](<Writers.md>)) [The Age of the Essay](<The Age of the Essay.md>)
            - or [germans]([Germany](<Germany.md>))    
        - Examples of multi-word
            - [ISAs]([Income Share Agreements](<Income Share Agreements.md>))
            - test whether this appears [x](((XFgHjPHJy)))
- ## #[New Features](<New Features.md>) - [Query](<Query.md>) component
    - How it works
        - ```
{{query: {and: [TODO](<TODO.md>) 
          {not: 
           {or: [Example](<Example.md>) [Demo](<Demo.md>)}}}}

will return all TODOs 
 that are not also tagged with Example or Demo
```
        - **TODOs which are not Demos or Examples** {{[query](<query.md>): {and: [TODO](<TODO.md>) {not: {or: [Demo](<Demo.md>) [Example](<Example.md>)}}}}}
        - How to write [Queries in Roam]([Query](<Query.md>))
            - There are three logical operators 
                - and
                - or
                - not
            - A query can look for block or page references
            - Queries look like this
            - `{` {{or: or: | not: | and:}}  {{or: ((65J8uNv6D))} | [Example](<Example.md>)]}} `}`
            - but they can compose
                - so you can have
                    - ```javascript
{{query: {and: [Questions](<Questions.md>) {not: [important](<important.md>)}}}}```
                        - gets you Questions that are not important
                    - ```{{query: {or: [backlinks](<backlinks.md>) [Precise Links](<Precise Links.md>)}}}```
                        - gets you blocks that are tagged with backlinks OR precise links

# Backlinks
## [February 11th, 2020](<February 11th, 2020.md>)
- {{query: {and: [February 9th, 2020](<February 9th, 2020.md>)}

## [Roam Change Log](<Roam Change Log.md>)
- [February 9th, 2020](<February 9th, 2020.md>)

