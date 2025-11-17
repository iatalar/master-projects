# ☀️ Weather App

This project is a simple Weather Application built with **Python** and **Jupyter Notebook**.  
It retrieves real-time weather data from a weather API and displays essential information along with visual weather condition icons.

---

## 📌 Features

- 🌡️ Fetches real-time weather data based on city name  
- 🌤️ Includes day/night icon support  
- 💧 Displays temperature, humidity, wind speed, and general weather conditions  
- 📒 Fully implemented in a Jupyter Notebook for easy experimentation  
- 🖼️ Contains a complete set of weather icons  

---

## 📁 Project Structure

master-projects/
│
├── Weather_App.ipynb        # Main notebook file
└── icons/                   # Weather condition icons
    ├── 01d.png
    ├── 01n.png
    ├── ...
    └── search_icon.png

## 🚀 How to Run

### 1️⃣ Install Required Libraries
Before running the notebook, install necessary dependencies:

bash
pip install requests

### 2️⃣ Open the Notebook

jupyter notebook Weather_App.ipynb

### 3️⃣ Run all cells sequentially to fetch and display the weather data.

## 🔑 API Usage

This application uses a public weather API (e.g., OpenWeatherMap API) to retrieve real-time weather information.

You must provide your own API key inside the notebook

## 🖼️ Icons

All weather icons are stored inside the icons/ directory.
The icon pack includes both daytime (d) and nighttime (n) versions, matching the API’s weather code format.

Examples:
 - 01d.png → clear sky (day)
 - 01n.png → clear sky (night)