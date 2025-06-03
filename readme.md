# Voice Assistant Project

A Python-based voice assistant that leverages speech recognition, text-to-speech, Wikipedia search, browser and GUI automation, and Google Generative AI integration to automate tasks through voice commands.

---

## Features

- **Text-to-speech** using `pyttsx3`
- **Speech recognition** with `SpeechRecognition`
- **Date and time handling**
- **Wikipedia search** capability
- **GUI automation** via `pyautogui`
- **Web automation and search** with `pywhatkit` and `webbrowser`
- **Integration with Google Generative AI (Gemini API)**
- Additional automation features using native Python modules

---

## User-Manual:
 - Say 'Jarvis' keyword before the main command to activate
 - Say 'jarvis presentaion _topic' than the topic to creating presentation
 - Say 'Helix' for activating conversation mode of the AI
 - Say 'jarvis Whatsapp' to activate whatsapp
 - Say 'jarvis open _app_name' to open any program of the system
 - Say 'jarvis close' for closing a function
 - Say 'jarvis play _video_name' to play something on youtube
 - Say 'Jarvis english test' to give a IELTS standard speaking test with automated voice output

## Installation

1. Clone the repository or download the project files.
2. Create an API key from GEMINI API and replace "YOUR_API_KEY" with your own.
3. Login to these sites using Chrome: gamma.app, whatsapp, youtube
4. Install the required Python packages:

```bash
pip install pyttsx3 SpeechRecognition wikipedia pyautogui pywhatkit google-generativeai
