# Aura – Futuristic Voice Assistant



<p align="center">
  <a href="https://github.com/YOUR_USERNAME/aura-assistant/stargazers">
    <img src="https://img.shields.io/github/stars/YOUR_USERNAME/aura-assistant?style=social" alt="GitHub stars">
  </a>
  <a href="https://github.com/YOUR_USERNAME/aura-assistant/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/YOUR_USERNAME/aura-assistant?color=purple" alt="License">
  </a>
  <img src="https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white" alt="Python version">
  <img src="https://img.shields.io/badge/UI-Tkinter-orange?style=flat&logo=tkinter" alt="Tkinter">
  <img src="https://img.shields.io/badge/Status-Prototype-yellow?style=flat" alt="Project Stage">
</p>

## ✨ What is Aura?

**Aura** is a modern, voice-activated personal assistant with a **futuristic glassmorphism + neural orb visualization**.

Features include:
- Always-listening voice recognition
- Natural language command understanding
- Real-time animated interface (pulsing orb, orbiting particles, twinkling stars)
- Dark/light theme switching (persisted)
- Everyday tools: weather, calculator, timers, reminders, translation, web control, music, files…

Built entirely in **Python** using **Tkinter** + **pygame** — no web frameworks, no Electron.

## 🎬 Demo (highly recommended to add!)

<!-- Replace with your actual video link -->
https://user-images.githubusercontent.com/YOUR_ID/xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx.mp4

*(Tip: Record a 15–30 second screen capture showing voice commands + animations — it dramatically increases repo appeal)*

## 🔥 Key Features

| Feature                    | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| 🎤 Voice + Text Input      | `speech_recognition` (Google) + fallback text input                         |
| 🔊 Text-to-Speech          | Thread-safe `pyttsx3` with preferred female voice                           |
| 🌌 Neural Visualization    | Animated central orb, orbital rings, particles, dynamic starfield           |
| 🌓 Theme Switch           | Dark ↔ Light mode with JSON persistence                                     |
| 🌤️ Weather                | OpenWeatherMap API (auto city detection or custom)                          |
| 🧮 Calculator              | Safe math expression evaluation                                             |
| ⏰ Timer & Reminders       | Spoken notifications + in-memory scheduling                                 |
| 🌍 Translation             | `googletrans` support + dedicated UI panel                                  |
| 🎵 Music                   | YouTube search / local file playback                                        |
| 🌐 Web & Search            | Open websites, Google search, Google Maps directions                        |
| 📂 File Operations         | Safe open / create / list files                                             |
| 📜 Conversation History    | Scrollable chat log + export to text file                                   |

## 📦 Requirements

- Python **3.8** – **3.12** recommended
- Working microphone + speakers/headphones

### Core dependencies

```bash
pip install \
  speechrecognition \
  pyttsx3 \
  pygame \
  requests \
  geocoder \
  googletrans==4.0.0-rc1
