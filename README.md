# TwitchBot
This is a Twitch ChatBot that has a React and MUI/MaterialUI frontend, and NodeJS backend, with a MongoDB database. Once a Twitch ChatBot is established, this application gives numerous features and commands available to the streamer and their viewers. Through this TwitchBot, interaction between a streamer and their chat, along with people within chat is enhanced, being able to provide information on the stream along with numerous activities. 

## Table of Contents
- [Features](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Features)
- [Installation and Setup](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Installation-and-Setup)
- [Usage](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Usage)
- [Available Commands](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Available-Commands)
- [Contributing](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Contributing)
- [Licensing](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Licensing)
- [Warning](https://github.com/gbowne1/TwitchBot/blob/main/README.md#Warning)

## Features
- React and Material UI Frontend
- Points and Command Leaderboard
- Various Twitch commands (some of which remain in development)
    - 8ball, accountage, ban, commands, discord, donate, famousCommand, follwage, lurk, poll, project, quote, request, schedule, social, song, timeout, uptime, and weather

## Installation and Setup
1. Fork and clone the repository locally
2. Navigate to source folder of the repository
3. Install dependencies
```bash
npm install
```
4. [Create a Twitch bot](https://dev.twitch.tv/docs/irc/get-started/)
5. Create a .env file in the project root and add your Twitch bot credentials:
```bash
TWITCH_USERNAME=your_bot_username
TWITCH_PASSWORD=your_oauth_token
TWITCH_CHANNEL=channel_to_join
```

## Usage
To start the Twitch bot, run:
```bash
npm start
```
The bot will then connect to the Twitch channel chat and listen for commands and respond.

## Available Commands
The bot will support the following commands:
    !accountage: Shows how old the user's Twitch account is.
    !ban <username>: Bans a user from the channel (moderator/broadcaster only).
    !commands: Displays a list of available commands.
    !discord: Provides a link to the designated Discord server.
    !followage: Shows how long the user has been following the channel.
    !project <project_name>: Sets or updates the current project being worked on.
    !timeout <username> <duration>: Times out a user for a specified duration (moderator/broadcaster permission only).
    !uptime: Displays the channel's uptime.

## Contributing
If you wish to contribute to this project, head over to [Contributing.md](https://github.com/gbowne1/TwitchBot/blob/main/CONTRIBUTING.md) for more information.

## Licensing
For more information on the licensing of this project, refer to [LICENSING](https://github.com/gbowne1/TwitchBot/blob/main/LICENSE)

## Warning
[Under Construction] Please do not use this in production. There is no guarantee this will connect to Twitch Chat.
It will need significant work in order to be used with Twitch and or connect to it's services.

