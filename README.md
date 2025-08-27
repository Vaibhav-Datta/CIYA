## 🤖 CIYA – Customizable Interface for Your Access

CIYA is a voice-activated personal assistant built in Python, designed to perform everyday tasks through natural speech interaction. Created by **Mr. Vaibhav Datta**, CIYA can search the web, remember information, open apps, tell the time, and even shut down your system—all with your voice.

## 🧠 Features

- 🎙️ Voice Recognition using Google Speech Recognition
- 🗣️ Text-to-Speech replies via gTTS and playsound
- 🕰️ Time-Based Greetings (Good morning/afternoon/evening)
- 🔍 Google Search integration
- 📧 App Launcher: Gmail, WhatsApp Web, YouTube, Google
- ⏰ Tells current time
- 📝 Memory System:
  - Remembers custom phrases
  - Stores key-value pairs for later retrieval
- 🛑 Sleep & Shutdown Modes via voice command
- 💬 Friendly Personality with responses to compliments and greetings

## 🧠 How CIYA Thinks
CIYA operates in two modes:

Sleep Mode: Waits for activation via phrases like "wake up" or "power on"

Command Mode: Executes tasks based on recognized voice commands

It uses a simple dictionary-based memory system to store and retrieve custom data.

## 🙋‍♂️ Creator
Developed by Mr. Vaibhav Datta CIYA is a passion project aimed at making voice interaction more personal and customizable.

## 🚫 License & Usage
CIYA is not open source and is not permitted for public use, redistribution, or modification. This project is a private build and intended solely for personal experimentation and development by the creator.

## 🗂️ File Structure
ciya.py           # Main assistant script
memory.txt        # Stores remembered data (auto-created)
README.md         # Project documentation

## 🚀 Getting Started

### Prerequisites

*Install the required Python packages:

```bash
pip install SpeechRecognition gTTS playsound wikipedia pyaudio


