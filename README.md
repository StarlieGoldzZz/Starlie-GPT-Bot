# Discord-Chat-Bot
This is an example Discord Chat Bot based on Open Ai and Discord.js Library. This code is capable of remembering the previous conversations and can reply accordingly.

## Requirements
- A Discord Bot with its Token.
- OpenAIApi Key.

## Startup
- Create a file named `.env`.
- Enter the following details to it:
```
token="YOUR TOKEN"
OPENAI_API_KEY="API KEY"
```
- https://discord.com/developers/applications
- Open Ai API Key [Get Key from here](https://platform.openai.com)

- In config.json, enter the channel-id's in which you want to enable the bot.
- Save the file. Open Terminal in the Project Directory.
- Run:
```
npm i
node index.js
```
- You are done.

## Configuration
To get Custom Response, just head to `prompt` variable, and change things accordingly. Do not add so many information, otherwise you will expire your free credits quickly.

## Troubleshooting
- Error: Status Code 500 : This means there is an server error from OpenAi
- Error: Status Code 429 : You have been rate-limited from OpenAi (you probably need to spend at least 5$ for it to work well)
