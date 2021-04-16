
# Backlinks
## [JSON Schema](<JSON Schema.md>)
- **[description](<description.md>):** The title of a page. The string is unique across a user's database. If importing a title that is already used, it will merge with the already existing content.
        - **[type](<type.md>):**

- **[description](<description.md>):** The string of a block
        - **[type](<type.md>):**

- **[description](<description.md>):** The unique identifier of a block. Use this if you want to preserve block references. If the unique identifier conflicts with other uid's in the database or the import, the import will fail. Be careful using this attribute. Standard Roam uid's are 9 characters, but can be any length. Roam uses naniod.js to generate these
        - **[type](<type.md>):**

- **[description](<description.md>):** An array of blocks, the order is implicit from the order of the array
        - **[type](<type.md>):**

- **[description](<description.md>):** The time the object was created, measured in ms since unix epoch. If not supplied, the create-time of the object will be filled in by either the edit-time, or now.
        - **[type](<type.md>):**

- **[description](<description.md>):** The time the object was last edited, measured in ms since unix epoch. If not supplied, the edit-time of the object will be filled in by either the create-time, or now.
        - **[type](<type.md>):**

- **[description](<description.md>):** The email of the user who last edited the object. If not supplied, will be filled in by the create-email, or the user who uploaded the JSON.
        - **[type](<type.md>):**

- **[description](<description.md>):** Determines what heading tag to wrap the block in, default is no heading (0)
        - **[type](<type.md>):**

- **[description](<description.md>):** The text-align style for a block
        - **[type](<type.md>):**

