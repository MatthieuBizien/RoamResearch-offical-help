- An Official Capture [Apple Shortcut](<../Apple Shortcut.md>), built by the Roam team!
- Link to install latest version: https://www.icloud.com/shortcuts/ae1ae833cada4999b44d9ac5dda2dc6d
- For issue reports or enhancement requests, please email us at support@roamresearch.com
- [Getting started](<../Getting started.md>) guide
    - **Requirements**
        - apple devices only (iphone, ipad, mac, apple watch, etc.)
        - Need an OpenAI API key for transcription & optional post-processing. 
            - if you do not have one, [we go through how to create one in the steps below](((aDWglI-Kc)))
    - **Steps**
        1. Follow this link for the shortcut: 
            - Link to install latest version: https://www.icloud.com/shortcuts/ae1ae833cada4999b44d9ac5dda2dc6d
        2. Click on "Set up Shortcut" & Enter your graph's name to get started
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2F4NhOVxidxj.png?alt=media&token=584eebcc-f599-4161-ae57-7780b93edbad)
        3. Get an "append-only" Roam API token
            1. settings > graph > new API token.
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2F9Gh3M3ld3n.png?alt=media&token=ba249458-3c91-4d93-b16f-4ea51aff9692)
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FOZjsD2LXfT.png?alt=media&token=2ded5da1-1ce4-4cdf-a36e-daca2a836dcb)
            2. In the next screen, enter a description for the token and change the scope to `append-only`
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FlX6xBAiHfr.png?alt=media&token=292a6d60-61f8-445d-8f54-93202e035378) 
            3. In the next screen, click on the "Clipboard" icon 📋 to copy the token to your clipboard. It will start with "roam-graph-token-"
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FY9eaz1nLPq.png?alt=media&token=f1313b19-48c6-48b4-9b94-3f09e1428da4)
        4. insert the token in the shortcuts app
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FekZcU5SwMo.png?alt=media&token=256b5341-8a1c-42be-b17f-59bb3c897ac5)
        5. In the next screen, leave empty if you want to capture to the daily note, otherwise, enter the title of the page you want to ✨speak to✨
        6. create your OpenAI API keys: 
https://platform.openai.com/api-keys > create new secret key
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FOXQWJaiNIU.png?alt=media&token=04e3ec26-2598-4e5c-9ae2-b3f9619e65fd)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FO9lLlQUoZK.png?alt=media&token=12407bea-2bd1-4399-87cf-4cbfcca13e28)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2F7smKjTiyq7.png?alt=media&token=6f05159b-19f6-4aac-ac43-50a8d70dc860)
        7. Enter the OpenAI API keys into the shortcut
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FUvoleX91uT.png?alt=media&token=8810edc9-e7b0-48f9-b737-be3402f7ed75)
        8. Few configuration steps regarding if we want to post-process, if we want to save the raw transcript if so, and if we want to change the post-processing prompt
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FN4laXM_ucp.png?alt=media&token=8e395772-3c5d-4c18-b0f8-ee874746bb93)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FSmYVPLruZv.png?alt=media&token=50ddbd07-8a40-4d57-897d-34c45d627c2a)
            - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2F3HC7XZ3_TR.png?alt=media&token=293284db-b653-4121-837f-6793e98bc4ba)
            - 
        9. Congrats! Now you can speak to your graph!
- [Change Log](<../Change Log.md>)
    - small change to the behavior for capturing to Daily Note pages [October 26th, 2024](<../October 26th, 2024.md>) - **no action needed on your side!**
        - It turns out that Apple broke some shortcut-related behavior in iOS 18 and that caused this Apple Shortcut to fail if it was set up to save to the daily note page.
        - We made a backend change and it should be working now (abeit with some difference in how the captured text looks like)
        - **tldr; ** No action needed on your side. The shortcut should work for all iOS, ipadOS and MacOS versions 
        - The difference in how the captured text looks like:
            - **What it looked like previously**
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FDkfchB8dQC.png?alt=media&token=e42425a2-ad96-495f-91e4-5db849cfb44f)
            - **What it looks like now**
                - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FPHs713Dv43.png?alt=media&token=effeaae6-dfea-4b06-a8b7-3ccc3f4695c2)
        - We will be releasing a new version soon-ish that fixes this change (and have a few new features), but this was the only way we could make the current and older versions of the Apple Shortcut to still work on the new OS
    - v1.3.0: https://www.icloud.com/shortcuts/ae1ae833cada4999b44d9ac5dda2dc6d
        - **Improvements**
            1. We now support both encrypted graphs and unencrypted graphs
                - On encrypted graphs, you can create an "append-only" token!
            2. Captures to today's Daily Notes Page by default
                - Captures are stored under a block/capture group `[Speak to Roam](<../Speak to Roam.md>) Captures`
                    - ![](https://firebasestorage.googleapis.com/v0/b/firescript-577a2.appspot.com/o/imgs%2Fapp%2Fhelp%2FHju0azD0Rk.png?alt=media&token=0aeb4cfa-8d59-45d0-bc34-e498769a94b1)
                - If you do not want to capture to DNP, you can alternatively pass an input page to capture underneath!
            3. More resilient to shortcut failure (If shortcut fails, you can find the recordings in Files in `Shortcuts/SpeakToRoam/FailedRecordings`. If it suceeds, you can find them in `Shortcuts/SpeakToRoam/HandledRecordings`. Behavior slightly different on Apple Watch)
            4. Shortcut is now available on the Share Sheet without extra configuration
                - You can use this to share recordings from the Voice Memos app to Roam via the shortcut!
    - v1.2.0
        1. 1. additional optional GPT4 API post processing step after transcription (records the output in a single roam block. Later, you can easily copy paste the block contents to get a nested structure)
        2. 2. The initial check of no internet should be faster (since we do a GET request to google.com now)
    - v1.1.0
        1. If no internet, fail immediately
        2. If recording has been made and then something fails (Whisper API or Roam Backend), then save the recording to “iCloud Drive/Shortcuts/SpeakToRoam/FailedRecordings/” folder and show a proper error message to the user

# Backlinks
## [Change Log](<Change Log.md>)
- ### Improved [Speak to Roam Apple Shortcut]([Apple Shortcuts/Speak to Roam](<../Apple Shortcuts/Speak to Roam.md>))

- Apple users might want to check out **[Speak to Roam]([Apple Shortcuts/Speak to Roam](<../Apple Shortcuts/Speak to Roam.md>))

## [Developer Documentation](<Developer Documentation.md>)
1. **[Speak to Roam]([Apple Shortcuts/Speak to Roam](<../Apple Shortcuts/Speak to Roam.md>))

## [Pipedream Workflows](<Pipedream Workflows.md>)
- **Alternative:** If your use case is that you have a lot of small recordings/voice memos that you want to send to Roam, and if you are in the Apple Ecosystem, please checkout our [Apple Shortcuts/Speak to Roam](<../Apple Shortcuts/Speak to Roam.md>)

- **Alternative:** If your use case is that you have a lot of small recordings/voice memos that you want to send to Roam, and if you are in the Apple Ecosystem, please checkout our [Apple Shortcuts/Speak to Roam](<../Apple Shortcuts/Speak to Roam.md>)

## [Speak to Roam](<Speak to Roam.md>)
- you probably want to visit [Apple Shortcuts/Speak to Roam](<../Apple Shortcuts/Speak to Roam.md>)

