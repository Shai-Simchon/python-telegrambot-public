this script was build to get nofications from telegram by sending a simple url request.

you need for this script:
personal bot
chat id
telegram bot token

***
for getting the Chat id, just send a random massage to your bot and after that run the script below. -replace "YOUR TELEGRAM BOT TOKEN" with your bot token.

import requests TOKEN = "YOUR TELEGRAM BOT TOKEN" url = f"https://api.telegram.org/bot{TOKEN}/getUpdates" print(requests.get(url).json())
***
