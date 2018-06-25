# WebexTeamsBotToGoogleWithSMS

This quick walkthrough is intended to give you a very simple Webex Teams bot – it sends content from a Webex Teams space to a Google spreadsheet, and then texts your cell phone via the Tropo Scripting API.  Nothing too fancy, but easy to build on. The commands will be passed to the bot using mentions – so if the following command is typed into a room where the bot is a participant:

@botname hello

The bot will retrieve that command, process it, post the message to a blank Google spreadsheet and then relay the content to the Tropo API, which will then send a text to your cell phone with an alert. 
