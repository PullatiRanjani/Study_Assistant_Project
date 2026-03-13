   # 🎓 Study Assistant (Sarvam AI Flask API)

A simple Study Assistant API built using Flask that integrates with Sarvam AI services to provide language translation, text-to-speech, and speech-to-text features. The API can be tested using Postman.

---

## 🚀 Features

- 🌍 Text Translation API
- 🔊 Text to Speech (TTS)
- 🎤 Speech to Text (STT)
- ⚡ REST API built with Flask
- 🔐 Secure API key using .env file
- 🧪 API testing using Postman

---

## 🛠 Tech Stack

Python
Flask
Sarvam AI API
Requests Library
Python-dotenv
Postman

---

## ▶ How to Run

### 1️⃣ Create Virtual Environment

python -m venv venv

Activate it (Windows)

venv\Scripts\activate


### 2️⃣ Install Dependencies

pip install -r requirements.txt


### 3️⃣ Add API Key

Create a .env file

SARVAM_API_KEY=your_api_key_here


### 4️⃣ Run the Application

python app.py


### 5️⃣ Server Runs At

http://127.0.0.1:5001/

---

## 📡 API Endpoints

### Home

GET /

Returns API status message.


### Translate Text

POST /translate

Body Example

{
"text": "Hello",
"source_language": "en-IN",
"target_language": "te-IN"
}


### Text to Speech

POST /tts

Body Example

{
"text": "Hello world",
"language": "te-IN"
}


### Speech to Text

POST /stt

Upload an audio file using Postman.

---

## 📁 Project Structure

study-assistant/
│
├── app.py
├── requirements.txt
├── .env
└── README.md

---

## 🌍 Push Project to GitHub


### 1️⃣ Initialize Git

git init

### 2️⃣ Add Files

git add .

### 3️⃣ Commit

git commit -m "Initial commit"

### 4️⃣ Connect GitHub Repository

git remote add origin https://github.com/yourusername/study-assistant.git

### 5️⃣ Push to GitHub

git branch -M main
git push -u origin main

---

## 👩‍💻 Author

Ranjani

---

## ⭐ Future Improvements


- 📄 Add PDF reading with TTS
- 🌐 Add more language support
- 📱 Build frontend interface
- ☁ Deploy to cloud (Render / Railway)


