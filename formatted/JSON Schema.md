- **Description**
    - A schema for JSON import into Roam. A file being uploaded must be an array of pages. Keys not defined in the schema will be ignored.
- **Objects**
    - Page
        - **[description](<description.md>):** An object representing a page. The only required key is the title
        - **[keys](<keys.md>):**
            - title
            - children
            - create-time
            - edit-time
            - edit-user
    - Block
        - **[description](<description.md>):** An object representing a block. The only required key is the string
        - **[keys](<keys.md>):**
            - string
            - uid
            - children
            - create-time
            - edit-time
            - edit-user
            - heading
            - text-align
- **Keys**
    - title
        - **[description](<description.md>):** The title of a page. The string is unique across a user's database. If importing a title that is already used, it will merge with the already existing content.
        - **[type](<type.md>):** string
    - string
        - **[description](<description.md>):** The string of a block
        - **[type](<type.md>):** string
    - uid
        - **[description](<description.md>):** The unique identifier of a block. Use this if you want to preserve block references. If the unique identifier conflicts with other uid's in the database or the import, the import will fail. Be careful using this attribute. Standard Roam uid's are 9 characters, but can be any length. Roam uses naniod.js to generate these
        - **[type](<type.md>):** string
    - children
        - **[description](<description.md>):** An array of blocks, the order is implicit from the order of the array
        - **[type](<type.md>):** array of Blocks
    - create-time
        - **[description](<description.md>):** The time the object was created, measured in ms since unix epoch. If not supplied, the create-time of the object will be filled in by either the edit-time, or now.
        - **[type](<type.md>):** integer
            - Epoch time in milliseconds (13-digit numbers)
    - edit-time
        - **[description](<description.md>):** The time the object was last edited, measured in ms since unix epoch. If not supplied, the edit-time of the object will be filled in by either the create-time, or now.
        - **[type](<type.md>):** integer
    - edit-user
        - **[description](<description.md>):** The user who last edited the object. 
        - **[type](<type.md>):** json object of the format `{":user/uid" "ROAM-USER-UID"}`
    - heading
        - **[description](<description.md>):** Determines what heading tag to wrap the block in, default is no heading (0)
        - **[type](<type.md>):** integer, 0 | 1 | 2 | 3
            - For level of heading, 0 being no heading (the default) 1 heading h1, etc
    - text-align
        - **[description](<description.md>):** The text-align style for a block
        - **[type](<type.md>):** string, "left" | "center" | "right" | "justify"
            - By default is left (as determined by the browser defaults)
- **Example**
    - ```javascript
[{:title        "December 10th 2018"
  :create-email "josh@roamresearch.com"
  :create-time  1576025237000
  :children     [{:string   "[Meeting](<Meeting.md>) with [Tim](<Tim.md>)"
                  :children [{:string "Meeting went well"}]}
                 {:string "[Call](<Call.md>) with [John](<John.md>)"}]}
 {:title    "December 11th 2018"}]```
    - More (better) examples can be found by exporting roam to json
