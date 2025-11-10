# 🌦️ Weather App

A simple and responsive **React.js weather application** that displays real-time weather data (temperature, humidity, wind speed, and weather condition) for any city using the **OpenWeatherMap API**.

---

## 🚀 Features

* 🌍 Search weather by city name
* 🌤️ Displays temperature, humidity, and wind speed
* 🖼️ Dynamic weather icons based on weather conditions
* ⚡ Fetches real-time weather data from **OpenWeatherMap API**
* 📱 Clean and responsive UI built with React and CSS

---

## 🧰 Tech Stack

* **Frontend:** React.js
* **Styling:** CSS
* **API:** OpenWeatherMap API

---

## 📦 Installation & Setup

Follow these steps to run the project locally:

### 1. Clone this repository

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

### 2. Install dependencies

```bash
npm install
```

### 3. Create an environment file

Create a `.env` file in the root directory and add your OpenWeatherMap API key:

```
VITE_APP_ID=your_openweathermap_api_key_here
```

> 🔑 Get your free API key here: [https://openweathermap.org/api](https://openweathermap.org/api)

### 4. Run the app

```bash
npm run dev
```

Then open [http://localhost:5173](http://localhost:5173) in your browser.

---

## 📁 Folder Structure

```
src/
│
├── assets/              # All icons and images
├── components/
│   └── Weather.jsx      # Main weather component
├── Weather.css          # Styling for Weather component
└── main.jsx             # React entry file
```

---

## 🧠 How It Works

1. When the app loads, it automatically fetches the weather data for **London**.
2. You can search for any city in the input box.
3. The app fetches data from the OpenWeatherMap API and updates the UI dynamically.
4. Icons change according to the current weather condition (clear, cloudy, rain, snow, etc.).

---

## 🖼️ Preview

[Weather App Screenshot](./src/assets/Preview.png)

---

## 🙌 Acknowledgements

* [OpenWeatherMap API](https://openweathermap.org/api)
* [React.js Documentation](https://react.dev/)

---

## 🧑‍💻 Author

**Yashika Soni**
📧 soniyashika164@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/yashika-soni1/) | [GitHub](https://github.com/Yashika-code)

---
