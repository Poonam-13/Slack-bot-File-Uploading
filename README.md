# Slack-bot-File-Uploading 📁

Slack-Bot is a communication tool used by developers and companies to share information and communicate. It has grown very popular in recent years.

In this Golang project, we’re building a slack bot that uploads a file.
With so much technology available to individuals and corporations , you could have several different files uploaded to your stack server. Slack supports several file
types including standard images . Users can also ink videos that can be viewed directly from the link displaying the video content and play buttons in slack.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Installation

1.Clone the repository:
git clone: https://github.com/Poonam-13/Slack-bot-File-Uploading.git

2.Connecting to Slack from Golang:

``` 
mkdir slack-bot

cd slack-bot

go mod init 
```

3. Build the application:

   ``` go build ```

4. Install the required dependencies:

``` 
go get -u github.com/slack-go/slack

go get -u github.com/poonam-13
```

5. Set up a Slack app and obtain the necessary credentials (token, signing secret).

6. Configure the bot's credentials by either setting environment variables or creating a `config.json` file. See the [Configuration](#configuration) section for more details.

7. Run the application:

   ``` go run main.go ```
   

8. Invite the bot to your Slack workspace and grant the necessary permissions to upload files.


## Usage 🔥

1. Add the bot to a channel where you want to enable file uploading.

2. In the Slack chat interface, use the bot's designated commands to upload files. For example, you might use a command like `/upload <path-to-file>` to initiate the file upload process.

3. The bot will process the file and upload it to the specified channel.

4. The bot will respond with a success message and provide a link to access the uploaded file.

## Configuration

The bot requires the following configuration options:

- `SLACK_TOKEN`: The Slack bot token used for authentication.
- `SLACK_SIGNING_SECRET`: The Slack app's signing secret for verifying requests.

Make sure to replace the placeholder values with your actual credentials.

## Contributing✨
Contributions are welcome! If you'd like to contribute to the project.

## Acknowledgements
This project utilizes the official Slack API for interacting with the Slack platform.

## 🔗Connect with me: 📞

If you have any questions, feedback, or suggestions, please feel free to reach out:
<p align="left">
<a href="https://twitter.com/poooo_13" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="poooo_13" height="30" width="40" /></a>
<a href="https://linkedin.com/in/pooo13" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="pooo13" height="30" width="40" /></a>
<a href="https://discord.gg/#0888" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="#0888" height="30" width="40" /></a>
</p>




