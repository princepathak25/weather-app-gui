# Weather GUI App

A clean and aesthetic desktop weather application built using Python & Tkinter.
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
- Requests
- OpenWeatherMap API
- python-dotenv

---

## How to Run Locally

1️⃣ Clone the repository

git clone https://github.com/princepathak25/weather-gui-prince.git  
cd weather-gui-prince  

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
weather-gui-prince/
├── weather-app-gui-prince.py
├── .gitignore
├── LICENSE
└── README.md
```

---

## Made by Prince Pathak

Star this repository if you found it useful!

---

## License

Licensed under the MIT License.
