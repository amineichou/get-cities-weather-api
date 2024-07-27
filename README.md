# Get Cities Weather API (Web Scrapper) Express.js

A simple API built with Express.js to provide current weather information for cities.

## Features
- Retrieve current weather data for a lots of cities.
- Easy to use and extend.
- Developed with modern JavaScript practices.

## Installation
1. Clone the repository: `git clone https://github.com/amineichou/get-cities-weather-api.git`
2. Navigate to the project directory: `cd get-cities-weather-api`
3. Install dependencies: `npm install`
4. Start the server: `npm start` (The server will run at `http://localhost:3000`).

## API Endpoints
### `GET /get`
Fetch the current weather for a cities.

**Request Parameters:**
- `no param`

**Example Request:**
`curl "http://localhost:3000/get"`

**Example Response:**
```json
[
    {
        "city": "Adelaide",
        "temperature": "63 °F",
        "icon": "//c.tadst.com/gfx/w/svg/wt-2.svg"
    },
    {
        "city": "Luganville",
        "temperature": "84 °F",
        "icon": "//c.tadst.com/gfx/w/svg/wt-17.svg"
    },
    {
        "city": "Alice Springs",
        "temperature": "84 °F",
        "icon": "//c.tadst.com/gfx/w/svg/wt-1.svg"
    },
    {
        "city": "Majuro",
        "temperature": "80 °F",
        "icon": "//c.tadst.com/gfx/w/svg/wt-17.svg"
    },
    ...
]
```
