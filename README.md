# GUI Weather App
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/Tkinter-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenWeather API](https://img.shields.io/badge/OpenWeather_API-FFB400?style=for-the-badge&logo=openweathermap&logoColor=white)

A clean desktop weather application built using Python & Tkinter.
It fetches real-time weather data from the OpenWeatherMap API and presents it in a simple, user-friendly GUI.

---

## Features

- Search weather by city name
- Displays temperature, humidity & weather conditions
- Handling of invalid city names
- Secure API key handling using environment variables
- Minimal Tkinter UI
- Fast and lightweight desktop application

---

## Tech Stack

- Python
- Tkinter
- OpenWeatherMap API

---

## How to Run Locally

1️⃣ Clone the repository

git clone https://github.com/princepathak25/weather-app-gui.git  
cd weather-app-gui 

2️⃣ Install dependencies

pip install -r requirements.txt  

3️⃣ Set up environment variables

Create a file named `.env` in the project root directory and add:

OPENWEATHER_API_KEY=your_api_key_here

Note: The `.env` file is ignored by Git and is never pushed to GitHub.

4️⃣ Run the application

python weather-app-gui-prince.py  

---

## Project Structure
```text
weather-app-gui/
├── weather-app-gui-prince.py
├── .gitignore
└── README.md
```

---

## Author
**Prince Pathak**
