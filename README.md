# Mini Voice Assistant

A Python-based desktop voice assistant that automates everyday computer tasks using voice commands. The assistant combines Speech Recognition, Text-to-Speech, API integration, and desktop automation to provide a simple hands-free experience through an interactive PyQt5 graphical interface.

---

## Features

- 🎤 Voice Command Recognition
- 🔊 Text-to-Speech Responses
- 🌐 Open Websites
- 💻 Launch Desktop Applications
- 🌦️ Live Weather Updates
- 📅 Google Calendar Events
- 📖 Wikipedia Search
- 🔍 Google Search
- ▶️ Play YouTube Videos
- 📰 Latest News Headlines
- 🎵 Play Music
- ✉️ Send Emails
- 🧮 Solve Mathematical Expressions
- 📍 Current Location & Distance Finder
- 📝 Create Notes
- 😂 Random Joke Generator
- 🌐 Display Public IP Address
- 📸 Capture Screenshots
- 🗂 Hide/Unhide Files
- 📊 System Information (CPU, RAM, Battery)
- 🖥 Modern PyQt5 GUI

---

## Technologies Used

- Python 3
- PyQt5
- SpeechRecognition
- pyttsx3
- PyAutoGUI
- PyWhatKit
- Requests
- Pillow
- WolframAlpha API
- OpenWeather API
- Wikipedia API
- Google Calendar API

---

## Project Architecture

```
Mini-Voice-Assistant
│
├── main.py
├── gui.ui
├── requirements.txt
│
├── Jarvis/
│   ├── config/
│   ├── features/
│   └── utils/
│
└── README.md
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/Mini-Voice-Assistant.git
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure API Keys

Create a file named `config.py` inside:

```
Jarvis/config/
```

Add your credentials:

```python
weather_api_key = "YOUR_API_KEY"
email = "YOUR_EMAIL"
email_password = "YOUR_EMAIL_PASSWORD"
wolframalpha_id = "YOUR_WOLFRAMALPHA_APP_ID"
```

### Run the Project

```bash
python main.py
```

---

## How It Works

1. User speaks a command.
2. SpeechRecognition converts voice into text.
3. The command is processed.
4. The corresponding feature is executed.
5. The assistant responds using Text-to-Speech.
6. Results are displayed in the GUI when applicable.

---

## Python Concepts Used

- Object-Oriented Programming (OOP)
- Exception Handling
- File Handling
- Multithreading
- API Integration
- Modular Programming
- GUI Development
- Desktop Automation

---

## Future Enhancements

- ChatGPT Integration
- Offline Voice Recognition
- WhatsApp Automation
- Face Recognition Login
- Voice Authentication
- Smart Reminder System
- Voice Controlled File Manager
- NLP-based Conversation Support

---

## Author

**Anamu Yashwant**

Python Full Stack Developer

GitHub: https://github.com/Yash-psycho

---

## License

This project is developed for educational and learning purposes.
