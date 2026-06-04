# SkyCast

SkyCast is an immersive, modern weather web application designed to provide real-time weather information with beautiful, dynamic visuals. It uses open-source APIs to deliver accurate forecasts, interactive maps, and detailed weather metrics.

## Features

- **Real-Time Forecasting**: Get current conditions, hourly forecasts for the next 24 hours, and a comprehensive 7-day outlook.
- **Dynamic Sky Animations**: The app's background changes automatically based on the current weather conditions (e.g., clear, rainy, snowy) and time of day (day/night).
- **Interactive Map**: View a global weather map with selectable layers for temperature, precipitation, wind, and cloud cover.
- **Saved Cities**: Save your favorite locations for quick access and refresh their weather data all at once.
- **Detailed Metrics**: View in-depth statistics including UV index, Air Quality Index (AQI), wind direction compass, and precipitation charts.
- **Smart Insights**: Receive automated, human-readable advice based on current conditions (e.g., "Grab your umbrella — rain is expected.").

## Tech Stack

- **HTML5**: Semantic structure.
- **CSS3**: Vanilla CSS for styling, utilizing variables, flexbox, CSS Grid, and keyframe animations. No external UI frameworks are used.
- **JavaScript (ES6+)**: Handles all application logic, API fetching, and DOM manipulation natively.
- **Leaflet.js**: Used for the interactive weather map.

## APIs Used

- **Open-Meteo**: Provides weather forecast data and Air Quality Index (AQI) completely free and without an API key.
- **Open-Meteo Geocoding**: Used to search for cities and retrieve their coordinates.
- **OpenStreetMap (Nominatim)**: Used for reverse geocoding to identify a user's location based on their browser's geolocation.
- **OpenWeatherMap Tiles**: Used within the Leaflet map to provide visual layers for temperature, precipitation, wind, and clouds.

## Setup and Usage

1. Clone or download this repository.
2. Open `index.html` in any modern web browser or serve the directory using a local development server (e.g., Live Server in VS Code, Python's `http.server`).
3. Allow location access to view your local weather automatically, or use the search bar to find any city worldwide.

## Browser Support

SkyCast supports all modern browsers including Chrome, Firefox, Safari, and Edge. It utilizes modern CSS features like CSS Grid and Backdrop-filter for glassmorphism effects.

## License

This project is open-source and free to use or modify.
