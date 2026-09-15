# 🌦️ Weather Buddy AI

## 📌 About the Project

Weather Buddy AI is a simple AI-powered weather application developed using Python and Streamlit.

The application allows users to ask questions about the current weather in any city using natural language. It uses a Hugging Face Large Language Model (LLM) with Function Calling to identify the user's request and retrieve real-time weather information from the Open-Meteo API.
<img width="1477" height="697" alt="1" src="https://github.com/user-attachments/assets/dc26601a-83f2-440e-97f3-14d1b10dbbb0" />
<img width="988" height="303" alt="2" src="https://github.com/user-attachments/assets/28e69fc8-4ac6-41e0-8f5f-b78148ee3ba2" />

## ✨ Features

- Ask weather questions in natural language
- Get current weather information
- Display temperature in °C
- Display humidity percentage
- Display wind speed in km/h
- Uses Hugging Face LLM
- Uses Function Calling
- Uses Open-Meteo Weather API
- Simple and interactive Streamlit interface
- Supports different cities

## 🛠️ Technologies Used

- Python
- Streamlit
- Hugging Face
- Open-Meteo API
- Requests
- Python-dotenv

## 🔄 How It Works

```text
User Question
      ↓
Hugging Face LLM
      ↓
Function Calling
      ↓
get_weather()
      ↓
Open-Meteo API
      ↓
Weather Data
      ↓
AI Response
