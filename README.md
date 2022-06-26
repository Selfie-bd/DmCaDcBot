# DMCA-Delete-Bot
This is a very simple Telegram DMCA Delete Bot by [@selfie-bd](https://github.com/selfie-bd).

## Demo Bot:
<a href="https://t.me/DMCADcBot"><img src="https://img.shields.io/badge/Demo-Telegram%20Bot-blue.svg?logo=telegram"></a>

### Usage:
- Add Bot to Channel or Group as Admin with Delete Messages & Add Admin Rights.
- Forward DMCA Message to Bot in Private & Wait till it Deletes.

#### Note:
Bot can't delete 24 hours old Messages that's why using User Client. So when you will forward message to bot a User Client will Join your Channel or Group as Admin. That Client will Delete Messages.

## Host Bot:
Best if you Host on Heroku `#Abuse_Heroku` !

### Deploy to Heroku:
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/selfie-bd/DMCADcBot)

## Configs:
- `API_ID` - Get this from [@TeleORG_Bot](https://t.me/TeleORG_Bot)
- `API_HASH` - Get this from [@TeleORG_Bot](https://t.me/TeleORG_Bot)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `OWNER_ID` - Bot Owner ID.
- `TG_USER_SESSION` - User Client Pyrogram String Session using [@StringSessionGen_Bot](https://t.me/StringSessionGen_Bot)
- `MONGO_DB_URI` - MongoDB URI for Saving UserID & Broadcast.
- `LOGS_CHANNEL` - Logs Channel ID. Better Keep Channel Private!
- `UPDATES_CHANNEL` - Force Subscribe Channel Username. *(Optional)*

### Support Group:
<a href="https://t.me/groupdc"><img src="https://img.shields.io/badge/Telegram-Join%20Telegram%20Group-blue.svg?logo=telegram"></a>
