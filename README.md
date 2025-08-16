# 🌤️ Weather App (Python + PyQt5)

A Python-based weather application that retrieves real time weather data using an API. Featuring a GUI for city-based weather browsing, displaying conditions such as temperature and forecast. Built with Python, requests, and PyQt5

## Features
- **City-based** searching utilizing OpenWeatherApp external API
- Display screen:
  - Current temperature of the city (represented in °F)
  - Provides **weather forecast** (e.g. cloudy, sunny, raining, etc.)
  - An emoji to represent the forecast at the city
- **Utilized PyQt5 GUI** for fonts and layout of the application
- **Error handling** for invalid inputs, API errors, connection error, and other instances of errors

## 🛠️ Programming/Languages used
- **Python 3**
- **PyQt5** for GUI
- **Requests** library for API calling
- **OpenWeatherApp API**

## 📂 Project Structure
- weather_app.py # Main application to run the program
- README.md # Documentation

## ▶️ How to Run
1. Clone this repo
2. Install pip and requests and PyQt5
3. Get an API key from OpenWeatherApp (https://openweathermap.org/) and replace the api_key inside the weather_app.py file
4. Run the program within the file weather_app.py

## How to use the application
- Once the file has compiled and ran enter a city into the textbox and click the "Get Weather" button to display the city forecast
