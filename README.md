# 🌦️ Weather App

A sleek and responsive weather forecasting application that allows users to search for real-time weather conditions and 24-hour forecasts for any city worldwide using the OpenWeatherMap API.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Installation & Usage](#installation--usage)

## Features

- **City-Based Weather Search**: Enter any city name to retrieve its current weather data.
- **Current Weather Display**: Shows temperature (in °C), weather description, and an associated weather icon.
- **Hourly Forecast**: Displays forecasts for the next 24 hours in 3-hour intervals.
- **Responsive UI**: Modern, glassmorphism-inspired design that works on both desktop and mobile devices.
- **Error Handling**: Alerts the user if the city is not found or if there is an issue fetching data.

## 🖼️ Preview
<p align="center">
  <img src="https://github.com/user-attachments/assets/6bd8e69d-47bc-496a-b541-8695cfd4fefc" alt="Weather App UI" width="500">
</p>

## Technologies Used

- **HTML5** – For structure and markup.
- **CSS3** – For styling and responsive design.
- **JavaScript** – For fetching data from the API and updating the DOM.
- **[OpenWeatherMap API](https://openweathermap.org/)** – To retrieve weather data.

## How It Works

1. **User Input**: The user enters a city name and clicks the "Search" button.
2. **API Requests**:
   - The current weather data is fetched using the `/weather` endpoint.
   - The 5-day forecast data is fetched using the `/forecast` endpoint.
3. **Data Processing**:
   - The application converts the temperature from Kelvin to Celsius.
   - It extracts and displays the relevant weather details (temperature, description, and icon).
4. **Rendering**:
   - The current weather information is shown at the top.
   - The hourly forecast (for the next 24 hours, with 3-hour intervals) is rendered in a scrollable view.

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
## 🔑 Obtain an API Key

2. Sign up at [OpenWeatherMap](https://openweathermap.org/api) to get your **free API key**.

## ⚙️ Setup the Project

3. Open the `script.js` file in your project directory.

4. Locate the line with the API key and change it with your API Key:
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
   
5. Open the index.html file in your browser to launch the app and start checking the weather!



