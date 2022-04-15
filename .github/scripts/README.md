# Auto Rom Poster Bot
A simple Post Bot written in <a href='https://www.python.org'>Python</a> using <a href='https://pypi.org/project/pyTelegramBotAPI'>pyTelegramBotAPI</a> to post rom updates to telegram channel whenever there is an OTA update and even list a log of updated and not updated devices in private group.

## Instructions
Code is meant to be inside of a folder named `.github/scripts` and github actions script is meant to be inside of a folder named `.github/workflows` in the `OTA` repository

### 1. Adding secrets
Go to your repo `settings > secrets > new repository secret`, and add these secrets.
- `BOT_TOKEN`: Telegram bot token
- `CHAT_ID`: Telegram group/channel chat ID where the rom needs to be posted
- `PRIV_CHAT_ID`: Telegram group/channel chat ID where the logs need to be posted
- `STICKER_ID`: Telegram sticker ID (If added, the bot first sends sticker then the rom post)
- `BANNER_URL`: Telegraph URL of your rom banner/photo
- `NOTES`: Notes to add in rom post if you have any
- `GH_TOKEN`: Github access token to push changes to repo
<br><b>Note:</b> Bot should be added in the group/channel where the rom needs to be posted

### 2. Running the bot
After adding secrets the next thing is to run the bot. 
<br><b>We use Github Actions to run the bot</b>
-  Actions will automatically run if any changes are commited to the repo and rom will be posted
-  You can also run the bot by going to `actions > Rom Poster Bot > workflow-dispatch` and tap on run

## Credits
- [Ashwin DS](https://github.com/geek0609)
