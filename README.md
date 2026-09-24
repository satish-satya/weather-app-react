# Weather App (React)

A simple weather web app built with React and Vite. Search any city and see the current weather and a 5-day forecast.

## Features
- Search weather by city name
- Current temperature, humidity and wind speed
- 5-day forecast (max/min temperature)
- Loading and error messages (for example, when a city is not found)
- Responsive layout that works on mobile and desktop

## Tech Used
- React JS (useState, forms, conditional rendering)
- JavaScript (async/await, fetch API)
- CSS (flexbox and grid)
- [Open-Meteo API](https://open-meteo.com/) (free, no API key needed)

## How to Run
1. Install Node.js
2. Open a terminal in this folder and run:
   ```
   npm install
   npm run dev
   ```
3. Open the link shown in the terminal (usually http://localhost:5173)

## What I Learned
- Calling two APIs one after another (city name to coordinates, then coordinates to weather)
- Handling loading and error states in React
