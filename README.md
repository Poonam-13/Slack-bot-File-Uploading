# Slack-bot-File-Uploading

Slack-Bot is a communication tool used by developers and companies to share information and communicate. It has grown very popular in recent years.

In this Golang project, we’re building a slack bot that uploads a file.
With so much technology available to individuals and corporations , you could have several different files uploaded to your stack server. Slack supports several file
types including standard images . Users can also ink videos that can be viewed directly from the link displaying the video content and play buttons in slack.

Connecting to Slack from Golang:
mkdir slack-bot
cd slack-bot
go mod init
go get -u github.com/slack-go/slack
go get -u github.com/poonam-13

Execute the program by running the main function:
go run main.go

Using the Slack Events API:
The slack events API is a way to handle events that occur in the Slack channels. There are many events, but for our bot, we want to listen to the mentions event.
