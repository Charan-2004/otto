🤖 Otto – Your Flirty AI Voice Assistant 💬
Otto is a custom-built Python voice assistant that’s more than just functional—it’s got personality! Designed to behave like a witty companion, Otto flirts, reminds you to hydrate, recalls past conversations, and reacts with expressive tones and dramatic pauses. It's a desktop-based AI you can toggle on/off anytime.

🛠 Features
🎙️ Voice Interaction: Understands voice commands and responds using speech synthesis.

🧠 Mini Memory System: Remembers important details like your name, birthday, and more using memory.json.

😏 Flirty Personality: Adds charm with dramatic pauses, giggles, and varied tones.

🕒 Hydration Reminders: Gently reminds you to stay hydrated during the day.

📶 Wi-Fi Access Ready: Designed to integrate web access features (news, weather, etc.).

🖥️ Toggleable Windows App: Enable or disable Otto with a simple click—runs in the background when on.

🧰 Tools & Technologies Used
Python (Core Language)

speech_recognition – Voice command input

pyttsx3 / gTTS – Text-to-speech (flavored with tone + pauses)

json – Persistent memory for important info

tkinter – GUI for Windows app toggle

threading – Background listening

PyInstaller – Packaged into an executable Windows app

VS Code – Development environment

🚀 Getting Started
1. Clone the Repo
bash
Copy
Edit
git clone https://github.com/yourusername/otto-voice-assistant.git
cd otto-voice-assistant
2. Install Requirements
bash
Copy
Edit
pip install -r requirements.txt
3. Run Otto
bash
Copy
Edit
python otto.py
(Or double-click the otto.exe if you're using the packaged version)

📁 File Structure
bash
Copy
Edit
otto-voice-assistant/
│
├── otto.py               # Main app logic
├── memory.json           # Stores remembered facts
├── requirements.txt      # Python dependencies
├── gui.py (optional)     # Toggle GUI (if built separately)
└── README.md             # You're reading it!
🔐 Optional Features (Future Plans)
Web access for weather/news

Mood-based tone detection

Voiceprint authentication

Android version (via Kivy or JS-Python bridge)

💬 Sample Conversation
You: "Hey Otto, what's the time?"

Otto: "Hmm… it's 5:32 PM, just like the last time you broke my heart. 💔" 😏

👤 Author
Charan Ky
Built with ❤️, sarcasm, and Python.
Portfolio Website

