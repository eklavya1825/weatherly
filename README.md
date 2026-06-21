# Weather Dashboard

A simple weather application built using React and OpenWeatherMap API. This project allows users to search for weather information of different cities and view current weather conditions along with a 5-day forecast.

## Features

* Search weather by city name
* Display current temperature and weather condition
* View humidity, wind speed, pressure, and visibility
* 5-day weather forecast
* Dark and Light theme support
* Temperature conversion between Celsius and Fahrenheit
* Recent search history using Local Storage
* Current location weather using Geolocation API
* Air Quality Index (AQI)
* Responsive design for mobile, tablet, and desktop

## Tech Stack

* React.js
* Vite
* Axios
* CSS Modules
* OpenWeatherMap API
* Local Storage

## Folder Structure

```text
src/
├── components/
│   ├── SearchBar/
│   ├── WeatherCard/
│   ├── ForecastCard/
│   ├── ForecastList/
│   ├── Loader/
│   ├── ThemeToggle/
│   ├── UnitToggle/
│   ├── RecentSearches/
│   └── ErrorBoundary/
├── hooks/
│   ├── useWeather.js
│   └── useLocalStorage.js
├── services/
│   └── weatherService.js
├── utils/
│   ├── formatDate.js
│   ├── temperatureConverter.js
│   └── weatherBackground.js
├── styles/
│   └── global.css
├── App.jsx
└── main.jsx
```

## Installation

### Clone the Repository

```bash
git clone <repository-url>
cd weather-dashboard
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory and add:

```env
VITE_OPENWEATHER_API_KEY=YOUR_API_KEY
```

### Run the Project

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:5173
```

## Build for Production

```bash
npm run build
npm run preview
```

## APIs Used

* Current Weather API
* 5-Day Forecast API
* Air Pollution API

All APIs are provided by OpenWeatherMap.

## How to Use

1. Enter a city name in the search box.
2. Click the Search button or press Enter.
3. View current weather details.
4. Check the 5-day forecast section.
5. Use the theme toggle to switch between dark and light mode.
6. Use the unit toggle to switch between °C and °F.
7. Click the location button to get weather information for your current location.

## Challenges Faced

* Handling invalid city names and API errors.
* Managing different weather API responses.
* Implementing responsive layouts for different screen sizes.
* Storing user preferences using Local Storage.

## What I Learned

* Building reusable React components.
* Working with REST APIs using Axios.
* Managing state with React Hooks.
* Using Local Storage for data persistence.
* Implementing responsive UI design.
* Handling asynchronous operations and errors.

## Future Improvements

* Hourly weather forecast
* Weather alerts and notifications
* Favorite cities feature
* Weather maps integration
* Better animations and UI enhancements

## License

This project is created for learning and internship purposes.
