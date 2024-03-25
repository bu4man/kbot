# kbot

Telegram bot on Go language. 

Bot can be found here:
https://t.me/k8s_devops_course_bot

Use below commands to build:

`~~gofmt -s -w ./ ~~` # not required, as format should be already correct

`go get` # To download all dependencies

`go build -ldflags "-X="github.com/bu4man/kbot/cmd.appVersion=v1.0.2`

Before start, TELE_TOKEN env variable needs to be set.

`Hint: use 'read -s TELE_TOKEN' and then 'export TELE_TOKEN' to define variable in a secure way.`

Use `./kbot start` to launch bot.

Available commands in Telegram are:
- /start 
- /start hello
