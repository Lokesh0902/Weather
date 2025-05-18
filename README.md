# 🌦️ Weather App

A sleek and responsive weather forecasting application that allows users to search for real-time weather conditions and 24-hour forecasts for any city worldwide using the OpenWeatherMap API.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Project Structure](#project-structure)
- [Installation & Usage](#installation--usage)

## Features

- **City-Based Weather Search**: Enter any city name to retrieve its current weather data.
- **Current Weather Display**: Shows temperature (in °C), weather description, and an associated weather icon.
- **Hourly Forecast**: Displays forecasts for the next 24 hours in 3-hour intervals.
- **Responsive UI**: Modern, glassmorphism-inspired design that works on both desktop and mobile devices.
- **Error Handling**: Alerts the user if the city is not found or if there is an issue fetching data.

## Demo
  
![Screenshot 2025-05-18 101455](https://github.com/user-attachments/assets/78ebf0ca-38cb-4da7-bd9c-69bbbf69dac5)


## Technologies Used

- **HTML5** – For structure and markup.
- **CSS3** – For styling, including glassmorphism effects and responsive design.
- **JavaScript (Vanilla)** – For fetching data from the API and updating the DOM.
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

## Project Structure

weather-app/
├── index.html # Main HTML file
├── style.css # Styling with glassmorphism and responsive design
├── script.js # JavaScript for API calls and DOM manipulation
└── preview.png # App screenshot (optional, for demo purposes)


## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
## 🔑 Obtain an API Key

1. Sign up at [OpenWeatherMap](https://openweathermap.org/api) to get your **free API key**.

## ⚙️ Setup the Project

2. Open the `script.js` file in your project directory.

3. Locate the line with the API key:
   ```javascript
   const apiKey = "YOUR_API_KEY_HERE";
4. Open the index.html file in your browser to launch the app and start checking the weather!



