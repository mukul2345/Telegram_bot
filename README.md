# Weather_Bot
The application is a Telegram bot that provides weather updates for cities. Users can subscribe to receive weather updates and get current weather data for specific cities.

# Weather Update Telegram Bot

![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-blue)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green)
![Express.js](https://img.shields.io/badge/Express.js-Framework-orange)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-red)
![Rest API](https://img.shields.io/badge/REST-API-blueviolet)

Telegram Bot Token:

Open Telegram and search for "BotFather".
Start a conversation with BotFather and follow the instructions to create a new bot.
Once your bot is created, BotFather will provide you with a token. Copy this token and use it as your Telegram bot token.
OpenWeatherMap API Key:

Go to the OpenWeatherMap website and sign up for a free account.
After signing up and verifying your email, log in to your account.
Navigate to the API keys section or settings to obtain your API key. Copy this API key and use it as your OpenWeatherMap API key.
MongoDB Connection String:

log in to your MongoDB Atlas account.
Create a new cluster if you haven't already done so.
Once your cluster is created, click on the "Connect" button and select "Connect your application".
You'll be provided with a connection string. Replace <password> with your MongoDB password and <dbname> with your database name.
Copy this connection string and use it as your MongoDB connection string.
Port Number:

Choose a port number that is not already in use by another application.
Commonly used port numbers for web applications are in the range of 3000 to 8000.
You can choose any available port number and use it as your application's port number.

This is a Telegram bot that provides weather updates for cities. Users can subscribe to receive weather updates and get current weather data for specific cities.

## Features

- Subscribe to weather updates
- Get current weather data for a specific city
- Unsubscribe from weather updates
- Get User's usernames
- Get Usage Statistics

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/mukul2345/weather-telegram-bot.git
   ```

2. Install the dependencies:

   ```shell
   cd weather-telegram-bot
   npm install
   ```

3. Configure environment variables:

   - Create a `.env` file in the project root directory.
   - Add the following environment variables:

     ```dotenv
     BOT_TOKEN=your-telegram-bot-token
     WEATHER_API_KEY=your-openweathermap-api-key
     MONGO_URI=your-mongodb-connection-string
     PORT=your-port-number
     ```

4. Start the application:

   ```shell
   npm start
   ```

5. Open Telegram and search for your bot by its username.
6. Start a conversation with the bot and use the available commands.

## Usage

- `/subscribe` - Subscribe to weather updates.
- `/unsubscribe` - Unsubscribe from weather updates.
- `/weather` - Get the current weather data for a specific city.
- `/help` - Display the list of available commands.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Telegraf (Telegram Bot Framework)
- Axios (HTTP requests)

## Creators

- Mukul

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contribute and make this Telegram bot even better!
