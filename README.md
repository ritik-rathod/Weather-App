# Weather App (JavaScript Project)

## Overview
This is a weather application built using HTML, CSS, and Vanilla JavaScript.  
It uses the OpenWeatherMap API to fetch real-time weather data based on user location and city search.

The project also includes a practice file for API testing and learning purposes.

---

## Features

### Main Weather Application (index.html)
- Get weather using current location (Geolocation API)
- Search weather by city name
- Displays:
  - Temperature
  - Humidity
  - Wind speed
  - Cloudiness
  - Weather description
- Tab-based UI (Your Weather / Search Weather)
- Loading state handling
- Error handling for invalid city
- Session storage used for saving coordinates

---

### Practice File (idx.html)
- Simple API testing file
- Fetches weather data for a fixed city (Indore)
- Displays minimum temperature
- Used for learning and experimentation with APIs

---

## Tech Stack
- HTML5
- CSS3
- JavaScript (ES6)
- OpenWeatherMap API
- Geolocation API
- Session Storage

---


## Setup Instructions

### 1. Clone the repository
git clone https://github.com/your-username/weather-app.git

---

### 2. Navigate to project folder
cd weather-app

---

### 3. Get API Key
Create an account on OpenWeatherMap and generate an API key:
https://openweathermap.org/api

---

### 4. Add API Key
Open index.js and replace:
const API_KEY = "YOUR_API_KEY";

---

### 5. Run the project
Open index.html directly in your browser.

---

## Important Notes
- Do not expose real API keys on GitHub
- Replace API key with "YOUR_API_KEY" before pushing
- idx.html is only for practice purposes

---

## Concepts Used
- Fetch API (async/await)
- DOM Manipulation
- Geolocation API
- Session Storage
- Event Handling
- Tab-based UI logic
- API error handling

---

## Future Improvements
- 5-day weather forecast feature
- Weather icons enhancement
- City autocomplete search
- Dark mode support
- Improved responsive design
