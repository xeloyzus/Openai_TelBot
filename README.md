# OpenAI Telegram Bot Project

This project provides a Telegram Bot interface for users to query and prompt OpenAI. The bot is designed to receive user input in the form of a text message, process the input using the OpenAI API, and return the response in the bot's chat.

# Requirements
To use this project, you will need:

- A Telegram account
- A Telegram Bot API token
- An OpenAI API key
- Java Development Kit (JDK) 8 or later
- Gradle build tool

# Installation
- Clone the project to your local machine:

git clone https://github.com/your-username/openai-telegram-bot.git

# Set your Telegram Bot API token and OpenAI API key as environment variables:

export TELEGRAM_BOT_TOKEN=<your-telegram-bot-api-token>
export OPENAI_API_KEY=<your-openai-api-key>

# Build the project:

- gradle clean build

# Run the bot:

java -jar build/libs/openai-telegram-bot-1.0-SNAPSHOT.jar

# Usage
- To use the bot, add it to a Telegram chat and send a message to the bot. 
- The bot will process your message using the OpenAI API and respond with the generated text.
- You can also send a message with the /prompt command followed by your prompt text. 
- The bot will use your prompt text as the input to the OpenAI API.

# Limitations
Please note that the OpenAI API has usage limits and you may be charged for usage beyond the free tier. You should also be aware of any legal or ethical implications of using the OpenAI API to generate text.

License
This project is licensed under the MIT License. See the LICENSE file for more information.
