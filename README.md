# 🌤️ Prince's Weather GUI App

A clean and aesthetic desktop weather application built using Python & Tkinter.
It fetches real-time weather data from the OpenWeatherMap API and presents it in a simple, user-friendly GUI.

---

## ✨ Features

- 🏙️ Search weather by city name
- 🌡️ Displays temperature, humidity & weather conditions
- ⚠️ Graceful handling of invalid city names
- 🔐 Secure API key handling using environment variables
- 🎨 Minimal and beginner-friendly Tkinter UI
- 🚀 Fast and lightweight desktop application

---

## 🛠️ Tech Stack

- Python
- Tkinter
- Requests
- OpenWeatherMap API
- python-dotenv

---

## 🚀 How to Run Locally

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

## 📁 Project Structure

weather-gui-prince/
├── weather-app-gui-prince.py
├── .gitignore
├── requirements.txt
└── README.md

---

## 🔐 Security Note

API keys are stored securely using environment variables (.env) and are never hardcoded into the source code.
This follows real-world development and security best practices.

---

## 📌 About the Creator

Built with 💙 by Prince Pathak  
An engineering student passionate about building practical, clean, and secure Python projects.

⭐ Star this repository if you found it useful!

---

## 📜 License

Licensed under the MIT License.
See the LICENSE file for details.
