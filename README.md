# File-Store-Bot
This is Telegram Parmanent Files Store Bot by [@ZauteKm](http://t.me/ZauteKm)


### Features:
- In PM Just Forward or Send any file it will save on Database & give you the Access Link.
- In Channel Add Bot as Admin with Edit Rights. When you will send any file or media in Channel it will Edit the Broadcast Message with Saved Link Button.
- You can also Broadcast anythings via this Bot.
- You can also Do Force Sub to a Channel to allow access the Bot.

### Demo Bot:
<a href="https://t.me/BetterFileStoreBot"><img src="https://img.shields.io/badge/Demo-Telegram%20Bot-blue.svg?logo=telegram"></a>

## Configs:
- `API_ID` - Get this from [my.telegram.org/app](https://my.telegram.org/app)
- `API_HASH` - Get this from [my.telegram.org/app](https://my.telegram.org/app)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `BOT_USERNAME` - You Bot Username. *(Without [@])*
- `DB_CHANNEL` - A Telegram Channel ID.
	- Make a Channel for Storing Files. We will use that as Database. Channel must be Private! Else you will be Copyright by [TGBotsProJect](https://t.me/TGBotsProJect)!
- `BOT_OWNER` - Bot Owner UserID
	- Put your Telegram UserID for doing Broadcast.
- `DATABASE_URL` - MongoDB Database URI
	- This for Saving UserIDs. When you will Broadcast, bot will forward the Broadcast to DB Users.
- `UPDATES_CHANNEL` - Force Sub Channel ID *(Optional)*
	- ID of a Channel which you want to do Force Sub to use the bot. 
- `LOG_CHANNEL` - Logs Channel ID
	- This for some getting user info. If any new User added to DB, Bot will send Log to that Logs Channel. You can use same DB Channel ID.

### Deploy Now:
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ZauteKm/File-Store-Bot)

## Commands:
```
start - start the bot

status - Show number of users in DB

broadcast - Broadcast replied message to DB Users
```

* **Language:** [Python3](https://www.python.org)
* **Library:** [Pyrogram](https://docs.pyrogram.org)
