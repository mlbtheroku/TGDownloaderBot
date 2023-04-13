# TGDownloaderBot

Telegram Downloader Bot

## Dev's Setup

+ ```pip install python-telegram-bot --upgrade``` or ```pip install python-telegram-bot -U --pre```
+ ```pip install python-telegram-bot[rate-limiter]```
+ ```pip install validators```
+ ```pip install -U yt-dlp```
+ ```sudo dnf install ffmpeg```
+ Create the ```config.properties``` file in the project's directory, and put this content:

```
[secrets]
telegram.token=XXX
telegram.group.id=-ZZZ
telegram.developer.chat.id=WWW
[application]
# log.level = info | debug | error
log.level=info
send.start.and.stop.message=false
# 1.1 | 2
http.version=1.1
```

### Setup BotFather

1. ```/setcommands```
2. ```@TG_DownloaderBot```
3. Copy paste this:

```
version - show bot's version
download - download a video from an url
shutdown - shutdown the bot
```

## BotFather creation's infos

Done! Congratulations on your new bot. You will find it at t.me/TG_DownloaderBot. You can now add a description, about section
and profile picture for your bot, see /help for a list of commands. By the way, when you've finished creating your cool
bot, ping our Bot Support if you want a better username for it. Just make sure the bot is fully operational before you
do this.

Use this token to access the HTTP API:
XXX
Keep your token secure and store it safely, it can be used by anyone to control your bot.

For a description of the Bot API, see this page: https://core.telegram.org/bots/api

## TODOs

+ ~~download from youtube video/mp3~~
+ ~~download from facebook~~
+ ~~download from instagram~~
+ ~~download from tiktok~~
+ https://youtube.com/shorts/rb4LEDH9EB8?feature=share timeout

## Links

+ https://www.gyan.dev/ffmpeg/builds/
+ https://github.com/yt-dlp/yt-dlp/
