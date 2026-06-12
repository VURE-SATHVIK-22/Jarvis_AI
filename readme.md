# Jarvis AI

A fully autonomous, always-listening AI personal assistant.

## Overview
Jarvis AI is an intelligent assistant capable of understanding voice commands, viewing the screen, interacting with browsers, and managing files. It features real-time voice interaction using Google Gemini, computer vision with OpenCV, and desktop automation.

## Features
- **Voice Interaction:** Real-time continuous listening and natural text-to-speech.
- **Vision:** Live camera processing and screen capture.
- **Automation:** Desktop control, web browsing, file management, and system settings manipulation.
- **Tools:** Flight search, weather reports, and game updates.

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/VURE-SATHVIK-22/Jarvis_AI.git
   cd Jarvis_AI
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv jarvis_env
   jarvis_env\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   playwright install
   ```

4. **Configuration:**
   Rename the config template in the `config/` directory and add your Google Gemini API key.

5. **Run:**
   ```bash
   python main.py
   ```

## Disclaimer
This AI has direct access to your system. Always supervise its actions and do not run with administrative privileges unless necessary.
