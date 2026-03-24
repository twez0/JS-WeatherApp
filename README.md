# WeatherApp (JS Edition)

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![OpenWeatherMap](https://img.shields.io/badge/API-OpenWeatherMap-orange?style=for-the-badge)

A dynamic, real-time weather web application that adapts its visual interface based on local time and current weather conditions.

[Live Demo](https://js-weather-app-sigma.vercel.app/)

---

## Key Features

*   **Smart Geolocation:** Automatically detects user location using `Geoapify API` and the browser's `Navigator Geolocation`.
*   **Global Search:** Instant weather updates for any city worldwide with error handling for invalid inputs.
*   **Dynamic Themes:** 4 distinct visual modes (Sunrise, Day, Sunset, Night) that sync with the local time of the selected city.
*   **Immersive Effects:** Visual layers for rain, mist, and varying cloud density implemented via dynamic CSS class manipulation.
*   **Unit Conversion:** Toggle seamlessly between Celsius (°C) and Fahrenheit (°F).
*   **Hourly Forecast:** Detailed cards showing upcoming weather, including humidity, pressure, wind gusts, and cloud cover.
*   **Persistence:** Remembers the last searched city using `localStorage`.

## Technical Stack

Built with **Vanilla JavaScript (ES6+)** using a modular architecture:

- **Asynchronous JS:** Leverages `async/await` and the `fetch` API for efficient data retrieval.
- **DOM Manipulation:** High-performance UI updates without external libraries.
- **Geocoding:** Reverse geocoding to translate coordinates into human-readable city names.
- **Modular Design:** Logic is decoupled into dedicated modules for API calls, UI rendering, event handling, and visual effects.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```
2. **Launch the project:**
   Open index.html using a local server (Live Server extension in VS Code). This is required because the project uses ES6 Modules.
   
