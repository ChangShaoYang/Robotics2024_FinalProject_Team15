# TM Robot Final Project (Team 15)

This repository documents my contribution to the **Robotics 2024 Final Project**, where our team developed a voice-interactive drawing system using a TM Robot Arm and ROS 2.  
I was mainly responsible for implementing the **speech-to-text component**, which converts voice commands into English text to drive downstream processes such as image generation and drawing.

---

## 🔧 Project Context

The full project includes:
- Canva localization
- Audio recording via microphone
- Speech-to-text conversion
- Translation to English
- AI Image generation
- Path planning and robot drawing via ROS 2 and TM Robot Arm

This module handles the **speech recognition and transcription** part of the workflow.

---

## 🎤 My Role: Speech-to-Text

### Responsibilities:
- Recorded voice commands from the user
- Converted speech into text
- Automatically translated to English
- Output string for later use in image generation

### Example Flow:
1. User says: 「我想要畫一隻貓」
2. Program records audio and transcribes: `I want to draw a cat.`
3. Passed to image generation module

---

## 🔗 Full Team Project Repository

The full project is hosted by our teammate here:  
👉 [https://github.com/HaoYuLiu0725/Robotics2024_FinalProject_Team15](https://github.com/HaoYuLiu0725/Robotics2024_FinalProject_Team15)
