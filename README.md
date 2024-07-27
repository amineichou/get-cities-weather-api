# Get Cities Weather API (Web Scrapper) Express.js

A simple API built with Express.js to provide current weather information for cities.

## Features
- Retrieve current weather data for any city.
- Easy to use and extend.
- Developed with modern JavaScript practices.

## Installation
1. Clone the repository: `git clone https://github.com/amineichou/get-cities-weather-api.git`
2. Navigate to the project directory: `cd get-cities-weather-api`
3. Install dependencies: `npm install`
4. Start the server: `npm start` (The server will run at `http://localhost:3000`).

## API Endpoints
### `GET /weather`
Fetch the current weather for a city.

**Request Parameters:**
- `city` (query parameter): The name of the city to get weather information for.

**Example Request:**
`curl "http://localhost:3000/weather?city=London"`

**Example Response:**
```json
{
  "city": "London",
  "temperature": "15°C",
  "condition": "Cloudy"
}
```
