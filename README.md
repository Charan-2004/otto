# 🤖 Otto – Your Flirty AI Voice Assistant

Otto is a desktop-based Python voice assistant with a personality. It responds to your voice commands, remembers your details, reminds you to hydrate, and even flirts with you. Built with Python and packaged for Windows, Otto is your talkative digital buddy—always listening, always charming.

---

## 🚀 Features

- 🎙️ **Voice Interaction** – Listens and replies with expressive speech
- 😏 **Flirty & Fun Personality** – Adds dramatic pauses, emotional tone, and reactions
- 🧠 **Mini Memory System** – Remembers your name, birthday, and facts using `memory.json`
- 💧 **Hydration Reminders** – Gentle alerts to keep you healthy
- 🖥️ **Toggleable Windows App** – Enable/disable Otto with one click
- 📶 **Wi-Fi Access Ready** – Future support for web-based tasks (weather, news, etc.)

---

## 🧰 Requirements

- Python 3.7+
- `pyttsx3`, `speechrecognition`, `pyaudio`, `json`, `tkinter`
- Windows OS (for `.exe` packaging & background toggle)
- Chrome (for future web-access tasks)
- [PyInstaller](https://pyinstaller.org/en/stable/) – for creating `.exe`

Install dependencies:
```bash
pip install pyttsx3 SpeechRecognition pyaudio
