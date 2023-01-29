# Feature Research

This is to research the existing features in the Polly Slack Bot

- Opening the Polly app (to DM it), you can see a fancy UI page with `Home` chosen by default, and other tabs like `Messages` to send messages and `About` tab for about section which also contains links to app configuration, home page. The about section also shows sample commands

- In Polly Home page in Slack App UI, `Create a Polly` button shows a form which has
    - `Create a Question` text box
    - `Question Type` drop down
    - `Enter Choices Below` text area
    - `Allow Comments` Toggle
    - `Allow multiple votes` Toggle
    - `Audience can add choices (single question polly only)` Toggle
    - `+ Add a Question` button
    - `Choose Audience` to choose Slack Channels or Users from list
    - `Send Polly as DM` Toggle
    - There's settings
        - Responses
            - Non-Anonymous
            - Anonymous
            - Confidential
        - Schedule - Send when?
            - Schedule
                - Send On - Date
                - Time
                - Frequency
                - Allow Voting for
                    - weeks/days/hours/minutes
            - Send Now
                - Allow Voting for
                    - weeks/days/hours/minutes
        - Results (dropdown)
            - In Realtime option
            - Show After Close option
            - Not Shown to Participants option


Questions
- What's a `Simple Poll` Slack app? How's it different from `Polly` Slack app?

---

Exploration
- Simple Poll App - https://simplepoll.rocks
    - Typing `/poll` opens up a dialogue box to create a poll, survey or brainstorm, which are all poll types, shown in a drop down. By default a poll creation form is shown with heading as `Create Poll`, when poll type drop down is used and a type is selected, accordingly the form content changes and the heading also changes to `Create Survey` or `Create Brainstorm`

    - When leaving the dialogue box with `Cancel` it asks `Are you sure you want to leave? It looks like you’re still working on this. You may lose the info you've entered so far if you leave now.` with options to `Keep Editing` vs `Leave`

    - Looks like the poll is created using `Simple Poll` and that app needs to be invited to private channels in case of private channels

---

Polly Alternatives or similar services
- https://geekbot.com/
- https://simplepoll.rocks/
- https://pollunit.com/en
- https://www.polleverywhere.com/
- https://quickpoll.io/
- https://www.advancedpoll.rocks/
