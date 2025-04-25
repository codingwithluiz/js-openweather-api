# 🌦️ JS OpenWeather API

A simple weather app using the OpenWeatherMap API, built with HTML, CSS, and JavaScript.

This project demonstrates how to fetch and display real-time weather data based on a user's input.

---

## 🔍 Features

- Search for any city by name
- Fetches current weather data from OpenWeatherMap
- Displays temperature, weather description, and city name
- Built with **vanilla JS**, no frameworks or libraries

---

## 📦 Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- OpenWeatherMap API

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/codingwithluiz/js-openweather-api.git
cd js-openweather-api
```

### 2. Add Your OpenWeatherMap API Key

Create a file called `config.js` in the project root (this file is ignored in `.gitignore`):

```js
const API_KEY = 'YOUR_API_KEY_HERE';
```

Or, if your code handles the key inline, update it directly in `script.js`.

### 3. Open the App

Just open `index.html` in your browser and try it out!

---

## 🧠 How It Works

1. User enters a city name.
2. JavaScript calls the OpenWeatherMap API using `fetch()`.
3. The app updates the DOM to display temperature and conditions.

---

## 🧪 Sample API Call

```
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
```

---

## ✨ Ideas to Improve

- Add weather icons from OpenWeatherMap
- Show humidity, wind speed, and more details
- Style it with modern UI frameworks
- Add geolocation to fetch weather automatically

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ by [@codingwithluiz](https://github.com/codingwithluiz)  
Watch more tutorials on [YouTube](https://www.youtube.com/@CodingWithLuiz)
