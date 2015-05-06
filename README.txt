SIMPLE PUSH SAMPLE for ActionScript
-----------------------------------

Please read the sample Guide for more information at: https://docs.gamedonia.com/samples/simple-push/as-tutorial


Instructions:
-------------

Before executing this sample, you need to create a game in the Gamedonia Dashboard. To create a Game in Gamedonia:

1) Log into the Gamedonia Dashboard at http://dashboard.gamedonia.com
2) Create a Game.
3) Copy your API key and Secret from the Game Information section.
4) Enable push notifications for iOS or Android following this guide: https://docs.gamedonia.com/guides/push-notifications/actionscript

In Flash Builder:

- Open the pushView.mxml file and fill the variables API_KEY and SECRET with the values you previously copied from the Dashboard.
- Open the simple_push-app.xml file and change your_google_project_id in the <manifest> tag with the value of your Project ID taken from the Google Developers Console (see push notifications guide above).

<meta-data android:value="PROJECT_ID: your_google_project_id " android:name="GOOGLE_PROJECT_ID"></meta-data>

For more information, check out our documentation at https://docs.gamedonia.com/