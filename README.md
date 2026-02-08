# Jarvis – AI Voice Assistant 🤖🎙️

Jarvis is a Python-based AI voice assistant inspired by Alexa and Google Assistant. It can listen for a wake word, understand voice commands, perform common tasks like opening websites, playing music, fetching news, and answering general questions using OpenAI.

---

## 🚀 Features

* 🎤 **Wake Word Detection** – Activates on the word **"Jarvis"**
* 🗣️ **Speech Recognition** – Converts voice commands into text
* 🔊 **Text-to-Speech** – Responds using natural-sounding voice
* 🌐 **Web Automation** – Open Google, YouTube, Facebook, LinkedIn, etc.
* 🎵 **Music Playback** – Plays songs via YouTube links
* 📰 **Live News Updates** – Reads top headlines (India)
* 🧠 **AI-Powered Answers** – Uses OpenAI (GPT-3.5) for general queries

---

## 🧩 Project Structure

```
├── main.py                 # Core voice assistant logic
├── openai_test.py          # Simple OpenAI API test script
├── musicLibrary.py         # Music dictionary with song links
├── temp.mp3                # Temporary audio file (auto-generated)
└── README.md               # Project documentation
```

---

## 🛠️ Tech Stack & Libraries

* **Python 3.x**
* `speech_recognition`
* `pyttsx3`
* `gTTS`
* `pygame`
* `webbrowser`
* `requests`
* `openai`
* `pocketsphinx` (optional, for offline recognition)

---

## 🔑 API Keys Required

You need the following API keys:

1. **OpenAI API Key**
2. **NewsAPI Key** ([https://newsapi.org](https://newsapi.org))

Replace placeholders in the code:

```python
api_key="<Your Key Here>"
newsapi = "<Your Key Here>"
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/jarvis-voice-assistant.git
cd jarvis-voice-assistant
```

2. **Install dependencies**

```bash
pip install speechrecognition pyttsx3 gtts pygame requests openai pocketsphinx
```

3. **Run the assistant**

```bash
python main.py
```

---

## 🧪 Example Commands

* "Jarvis open Google"
* "Jarvis open YouTube"
* "Jarvis play stealth"
* "Jarvis tell me the news"
* "Jarvis what is coding"

---

## 🧠 How It Works (High-Level)

1. Listens continuously for the wake word **Jarvis**
2. Captures the user command via microphone
3. Matches command with predefined actions
4. Falls back to OpenAI for intelligent responses
5. Converts response to speech and plays it

---

## ⚠️ Known Limitations

* Requires stable internet connection
* Wake word detection is basic
* Background noise may affect accuracy
* OpenAI model used is `gpt-3.5-turbo`

---

## 📌 Future Improvements

* Advanced wake-word engine
* GUI interface
* Offline AI responses
* Multi-language support
* Better error handling

---

## 👨‍💻 Author

**Ashutosh Gupta**
Aspiring Software Engineer | Python | AI Enthusiast

---

## 📄 License

This project is licensed under the MIT License – feel free to use and modify it.

---

⭐ If you like this project, don’t forget to star the repository!
