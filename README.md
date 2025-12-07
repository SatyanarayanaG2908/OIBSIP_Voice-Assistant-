<!--
  README for: Nova Voice Assistant (OIBSIP)
  Replace placeholder image paths (assets/...) with your actual images / GIFs.
-->

<p align="center">
  <img src="https://img.shields.io/badge/Project-Nova%20Voice%20Assistant-6f42c1?style=for-the-badge" alt="Nova Voice Assistant Badge" />
</p>

<h1 align="center">🎙️ Nova Voice Assistant</h1>

<p align="center">
  An AI-powered voice assistant built in <b>Python</b> using <b>Gradio</b>,<br/>
  with speech recognition, text-to-speech, weather, Wikipedia, safe calculations & more.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Framework-Gradio-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Speech-gTTS%20%2B%20SpeechRecognition-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Internship-Oasis%20Infobyte-ff69b4?style=for-the-badge" />
</p>

---

## ✨ Overview

**Nova** is an **AI Voice Assistant** that runs in **Google Colab** with a modern **Gradio UI**.  
It supports both **text** and **voice** commands, speaking back responses using **gTTS** and handling:

- Time & Date queries  
- Live Weather information (OpenWeather API)  
- Knowledge lookup via Wikipedia  
- Safe calculations with a custom `safe_eval` engine  
- Simple reminders  
- Session statistics & conversation history  
- Sanitized TTS so the voice output sounds natural and clean  

This project is part of my **Oasis Infobyte (OIBSIP)** internship.

---

## 🎬 Demo
<p align="center">
  <!-- Replace the below LinkedIn link with your actual demo post link -->
  <a href="(https://www.linkedin.com/posts/satyanarayanagattu_oasisinfobyte-oasisinfobyte-internship-activity-7403404636394590208-M7nY?utm_source=share&utm_medium=member_desktop&rcm=ACoAAF0JdNsB3Io7VkJeSkm-xsczfF3Y_GX3lSA)" target="_blank">
    <img src="assets/nova-demo.gif" alt="Nova Voice Assistant Demo" width="650" />
  </a>
</p>

> 🎥 **Demo Video:**  
> Watch the full demonstration of the Nova Voice Assistant on LinkedIn:  
> 👉 **www.linkedin.com/in/satyanarayanagattu**



---

## 🌟 Features

- 🎤 **Voice + Text Input**  
  - Speak using your microphone (audio upload in Colab).  
  - Or type commands directly in the **Text Chat** tab.

- 🕐 **Time & Date**  
  - “What time is it?”  
  - “What is today’s date?”

- 🌤️ **Weather Updates**  
  - “What’s the weather in Tokyo?”  
  - Uses **OpenWeather API** with your city of choice.

- 📚 **Knowledge via Wikipedia**  
  - “Tell me about artificial intelligence”  
  - “Who is Alan Turing?”

- 🧮 **Safe Calculations**  
  - “Calculate 156 divided by 12”  
  - Uses AST-based `safe_eval` to avoid executing unsafe code.

- ⏰ **Reminders**  
  - “Remind me to finish the project”  
  - Logs a timestamped reminder message.

- 🧠 **Session Intelligence**  
  - Conversation history (recent messages).  
  - Basic session stats: commands processed, successful responses, errors.

- 🔊 **Sanitized TTS Output**  
  - Rich markdown responses are cleaned into natural sentences.  
  - Removes emojis, links, symbols before sending to **gTTS**.

---

## 🧱 Tech Stack

- **Language:** Python 3.x  
- **UI Framework:** Gradio  
- **Speech Recognition:**  
  - `SpeechRecognition` (Google Speech API via internet)  
- **Text to Speech:**  
  - `gTTS` (Google Text-to-Speech)  
- **APIs:**  
  - OpenWeather API (for weather)  
  - Wikipedia API (via `wikipedia` library)  
- **Environment:**  
  - Google Colab (recommended)  
- **Others:**  
  - `requests`, `tempfile`, `ast`, `operator`, `re`, `html`

---

## 🎨 UI & Design

- The Gradio interface includes:
- Gradient header (“Nova Voice Assistant – Professional Edition”)
- Feature cards listing core capabilities
## Two tabs:
- 💬 Text Chat
- 🎤 Voice Input
- Conversation history accordion
- Auto-playing voice responses using gTTS
- Session statistics panel

<p align="center"> <!-- Replace with your own screenshot --> <img src="Nova.png" alt="Nova UI Screenshot" width="650" /> </p>
---


## 📈 Future Improvements
- Some ideas to extend Nova:
- 🗣️ Continuous listening (“Hey Nova” wake word)
- 🌐 Real web search integration (Google / Bing APIs)
- 🔐 User authentication / profiles
- 🧠 Context-aware multi-turn conversations
- 💾 Persistent reminders integrated with Google Calendar or system notifications
- 🌍 Multi-language TTS and recognition support

---

<p align="center"> Made with ❤️ using Python & Gradio<br/> <b>Nova Voice Assistant – OIBSIP Internship Project</b><br/> <i>Developed by Sri Venkata Satyanarayana Gattu</i> </p> `
