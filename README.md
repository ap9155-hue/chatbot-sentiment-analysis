# Note

This code is copied as a part of assignment (Prototype Simple Traditional Chatbot) for creating simple chatbot using anaconda and microsoft emulator. The reason for copying is to complete Assignment named Integrate Traditioanl Chatbot with AI Service Project for connecting with microsoft azure services.

# EchoBot

Bot Framework v4 echo bot sample.

This bot has been created using [Bot Framework](https://dev.botframework.com), it shows how to create a simple bot that accepts input from the user and echoes it back.

## To try this sample

- Clone the repository
```bash
git clone https://github.com/ap9155-hue/chatbot-sentiment-analysis.git
```
- In a terminal, navigate to `chatbot-sentiment-analysis` folder
- Activate your desired virtual environment
- In the terminal, type `pip install -r requirements.txt`
- Run your bot with `python app.py`

MacOS user has to run this command to set the environment variable in the activated environment
`export MicrosoftAIServiceEndpoint=<your endpoint>`
`export MicrosoftAPIKey=<your api key>`

## Testing the bot using Bot Framework Emulator

[Bot Framework Emulator](https://github.com/microsoft/botframework-emulator) is a desktop application that allows bot developers to test and debug their bots on localhost or running remotely through a tunnel.

- Install the latest Bot Framework Emulator from [here](https://github.com/Microsoft/BotFramework-Emulator/releases)

### Connect to the bot using Bot Framework Emulator

- Launch Bot Framework Emulator
- File -> Open Bot
- Enter a Bot URL of `http://localhost:3978/api/messages`

## Interacting with the bot and its capabilities

Welcome to the Chatbot! This bot is here to engage with you, provide useful responses. This bot can be connected with azure service with setting endpoint and api key from your activated environment.

This is the simple bot that does sentiment analysis from the connected service.

## Further reading

- [Bot Framework Documentation](https://docs.botframework.com)
- [Bot Basics](https://docs.microsoft.com/azure/bot-service/bot-builder-basics?view=azure-bot-service-4.0)
- [Activity processing](https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-concept-activity-processing?view=azure-bot-service-4.0)
- [Azure Bot Service Introduction](https://docs.microsoft.com/azure/bot-service/bot-service-overview-introduction?view=azure-bot-service-4.0)
- [Azure Bot Service Documentation](https://docs.microsoft.com/azure/bot-service/?view=azure-bot-service-4.0)
- [Azure CLI](https://docs.microsoft.com/cli/azure/?view=azure-cli-latest)
- [Azure Portal](https://portal.azure.com)
- [Channels and Bot Connector Service](https://docs.microsoft.com/en-us/azure/bot-service/bot-concepts?view=azure-bot-service-4.0)
