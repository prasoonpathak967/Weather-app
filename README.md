🌤️ React Weather App

A responsive weather forecasting web application built with React that fetches real-time weather data from a weather API and displays current weather conditions along with upcoming forecast details.

This project demonstrates API integration, component-based architecture, and dynamic UI updates using React state management.

📌 Project Overview

The React Weather App allows users to view weather information for a selected city.
The application retrieves weather data from an external weather API and displays:

Current temperature

Weather condition

Weather icons

Forecast for upcoming days

The project is designed using a component-based architecture, making it easy to maintain and extend.

🚀 Features
🌍 Search Weather by City

Users can search for weather information of a specific city.

🌡️ Real-Time Temperature Display

Displays the current temperature of the selected city.

🌤️ Weather Condition

Shows weather condition text and corresponding icon.

📅 Weather Forecast

Displays forecast information for the next few days.

⚡ API Integration

Fetches weather data using HTTP requests.

🎨 Responsive UI

Clean and responsive user interface styled using SCSS.

🛠️ Tech Stack
Frontend

React

JavaScript

HTML

CSS

SCSS (for styling)

Libraries & Tools

Axios for API requests

Node-Sass for styling

API

Weather API (Apixu / WeatherAPI)

📂 Project Structure
React-Weather-App
│
├── public
│   ├── index.html
│   └── manifest.json
│
├── src
│   ├── components
│   │
│   │   ├── top
│   │   │   ├── weather.jsx
│   │   │   ├── index.jsx
│   │   │   └── style.scss
│   │
│   │   └── bottom
│   │       ├── forcastday.jsx
│   │       ├── index.jsx
│   │       └── style.scss
│
│   ├── resources
│   │   └── images
│   │
│   ├── sass
│   │   └── app.scss
│
│   ├── App.jsx
│   ├── index.js
│   └── store.js
│
└── package.json
