🌤️ SkyCast — Weather Dashboard

A fully responsive weather dashboard that fetches live data from the OpenWeatherMap API — current conditions, hourly and 5-day forecasts, air quality, and sunrise/sunset tracking, all in a glassmorphism-styled UI.

Features


Live weather data by city search with autocomplete
Hourly forecast chart and 5-day outlook
Air Quality Index (AQI) with pollutant breakdown
Sunrise/sunset tracker with animated sun position
°C / °F unit toggle
Dark / light mode
Fully responsive across mobile, tablet, and desktop


Tech Stack


HTML, Tailwind CSS, vanilla JavaScript
OpenWeatherMap API for weather, forecast, and air quality data


Build Process

This project was built using an AI-assisted workflow:


Google Stitch generated the initial front-end UI from a detailed design prompt
Claude AI was used to convert the static design into a fully functional application — wiring up live API calls, building the search and autocomplete logic, implementing unit conversion, and fixing cross-device responsiveness
Manual testing and refinement across desktop, tablet, and mobile devices


This workflow reflects how I approach building projects efficiently: using AI tools for rapid prototyping and implementation, while directing the architecture, debugging real issues, and validating the result myself.

Run Locally

bashgit clone https://github.com/yourusername/skycast-weather-dashboard.git
cd skycast-weather-dashboard

Open index.html with a local server (e.g. VS Code Live Server) — opening directly as a file will block API requests due to browser security rules.

Note on API Key

The OpenWeatherMap API key in this project is on the free tier and used for demo purposes only.
