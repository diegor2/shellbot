About
===

This is a Dockerfile to run the shell telegram bot from https://github.com/jmendeth/node-botgram/

Build
===
    docker build -t diegor2/shellbot .

Run:
===
    docker run -e BOT_TOKEN <TOKEN> \
               -e BOT_USERID <YOUR-USER-ID> \
               diegor2/shellbot

To get a bot token:
---
[Ask the BotFather](t.me/BotFather)

To get your id:
---
[Ask the ID Bot](t.me/myidbot)
