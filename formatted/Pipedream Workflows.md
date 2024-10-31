- Pipedream is a no-code / low-code platform where one can build powerful workflows that connect your applications, services, APIs, and more
    - In other words, it is similar to [Zapier]([Zapier Integration](<Zapier Integration.md>)) but is more powerful and flexible (particularly if you can code a little bit)
        - If you do not know how to code, do not worry, the workflows below do not require any coding knowledge to set up
- Workflows
    1. ## **Audio file in Cloud Storage -> Transcript & Summary in Roam**
        - **Just upload an audio file to Dropbox/GDrive, and automatically get the transcript and summary in your Daily Note!!**
        - ### **What you will need**
            1. A Roam graph you want to capture to
                - This works even in encrypted graphs!
                - Won't work for local graphs though 😢
            2. An OpenAI API Key
                - we use OpenAI APIs for both [transcription](((xE-bNZ20Z))) and [summarization](((K1APaPuS-)))
                    - transcribing the audio file - uses __Whisper__
                    - summarizing the transcript - uses __gpt-4o-mini__
                - If you do not have an OpenAI API key, please go to https://platform.openai.com/api-keys > create new secret key
                    - Do note that api keys using the Trial credit are rate limited pretty hard by OpenAI. If you think you will use this workflow regularly, we recommend you set up billing, then create a new secret key and use that in this workflow
        - ### **Costs**
            - **tldr:** a little bit more than 0.36$ per hour of audio (or $0.006 per minute of audio)
                - as long as you do not have [very frequent usages](((UEgbI5Lzr)))
                    - **Alternative:** If your use case is that you have a lot of small recordings/voice memos that you want to send to Roam, and if you are in the Apple Ecosystem, please checkout our [Apple Shortcuts/Speak to Roam](<Apple Shortcuts/Speak to Roam.md>)
            - Breakdown
                - Whisper cost = **$0.006 / minute** (or eqvt 0.36$ per hour of audio)
                    - this should be the vast majority of the cost of using this workflow
                - Summarization (gpt-4o-mini) cost = **negligible**
                    - The cost for this should be much less than transcription since this is OpenAI's cheapest model till date
                - Pipedream: **Free (for non-heavy usage)** (details below)
                    - Pipedream's free plan is very generous (compared to competitors) and should be more than enough for regular usage
                    - Their free plan is 10 credits/day. Most voice recordings should only use up 1 credit.
                        - So, this means their free plan supports 10 voice recordings per day.
                    - You will probably only need to upgrade if you use this workflow more frequently or if you input larger files
                        - Larger files can take up multiple credits. For example, when testing with a podcast episode of 1.5 hours, it took up 3 credits
                    - **Alternative:** If your use case is that you have a lot of small recordings/voice memos that you want to send to Roam, and if you are in the Apple Ecosystem, please checkout our [Apple Shortcuts/Speak to Roam](<Apple Shortcuts/Speak to Roam.md>)
        - ### **Installation Process**
            - Please watch the video and use the links below
            - This workflow has two versions
                1. Google drive version: https://pipedream.com/new?h=tch_ovfa8o
                2. Dropbox version: https://pipedream.com/new?h=tch_8rf9P4
            - **[Loom video](<Loom video.md>) showing how to set up the workflow for yourself**
                - {{[video](<video.md>): https://www.loom.com/share/17c40a12022c476dbf85f5eb086e63eb}}
                - (Baibhav here: sorry for the long video 😅, this goes through setting up the workflow as well as any problems that might arise)
        - ### **Things to keep in mind** 
            - First, please watch [the video](((vOtWaKHnf)))!
            - When setting up the [Google drive version](((DtkYpItDq))), in the second step, `File` config might be empty. You NEED to enter `{{steps.trigger.event.id}}` there
                - this not being automatically set seems to be a bug in Pipedream
            - When setting up the [Dropbox version](((76mpf0cxk))), in the second step, the `Path` config might be empty. You NEED to enter `{{steps.trigger.event.path_lower}}` there
                - this not being automatically set seems to be a bug in Pipedream
            - If you run into any issues, please contact us at [support@roamresearch.com](mailto:support@roamresearch.com)
    2. Idea: weekly digest sent to your gmail
