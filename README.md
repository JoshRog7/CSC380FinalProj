# CSC380FinalProj

Weather Web Application

A full-stack weather application that provides real-time weather data, 7-day forecasts, and hourly temperature trends using multiple APIs. The app includes geolocation support, dynamic UI updates, and interactive data visualization.

---

Features

- Search weather by city name
- Use current location (geolocation support)
- 7-day weather forecast
- Hourly temperature chart (next 24 hours)
- Dark mode toggle
- Dynamic background based on weather conditions
- Autocomplete city search with debounce optimization

---

Tech Stack

Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)
- Chart.js (data visualization)

Backend
- Node.js
- Express.js

APIs
- OpenWeather API (current weather + geocoding)
- Open-Meteo API (forecast + hourly data)

---

Project Structure


project-folder/
 │
 ├── server.js # Express server
 ├── index.html # Main HTML file
 ├── style.css # Styling
 ├── script.js # Frontend logic & API calls
 └── package.json # Dependencies


---

Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/weather-app.git
cd weather-app
2. Install dependencies
npm install
3. Run the server
node server.js
4. Open in browser
http://localhost:3021
