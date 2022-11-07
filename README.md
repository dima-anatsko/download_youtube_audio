## The Simplest Youtube Audio Downloader Bot
___
The telegram bot downloads audio from YouTube.

Just send a link to a YouTube video and get audio. That's all! :blush:

## Deploy
___
The telegram bot is written in python and work through webhook.

Just following [this guide](https://habr.com/ru/post/655965/) if you want to deploy to Heroku for free.
You can run it locally, [the ngrok](https://ngrok.com/) is well suited for this.
Of course, you can deploy it on any server. :smirk:
### You need to set following environment variables:
```
BOT_TOKEN = your bot API token

WEBHOOK_HOST = your heroku host (example: https://myapp.herokuapp.com)

PORT : port for your app (optional parameter, default 8000)
```
