# AI-Integrated Tabletop Robotic Assistant for Human-Robot Interaction

An AI-integrated tabletop robotic assistant designed to interact with humans through speech, computer vision, emotion recognition, AI-generated responses, robotic motion, and visual expressions.

## 🤖 Project Overview

This project presents a compact and affordable tabletop robotic assistant capable of perceiving human presence, processing voice input, recognizing facial emotions, generating AI-based responses, and producing synchronized multimodal responses.

The system uses a Raspberry Pi 5 as the main processing unit and integrates artificial intelligence, computer vision, speech processing, servo-based motion control, audio output, and an LCD display.

## ✨ Key Features

- Face detection and recognition
- Facial emotion recognition
- Speech-to-text processing
- AI-based conversational responses
- Text-to-speech output
- Servo-based robotic movement
- LCD-based facial expressions
- Synchronized speech, motion, and visual responses
- Compact tabletop robotic design

## 🧠 AI & Software

| Component | Technology |
|---|---|
| Main Processor | Raspberry Pi 5 (8 GB) |
| Speech-to-Text | Whisper |
| Language Model | Ollama |
| Face Detection | MediaPipe |
| Face Recognition | dlib |
| Emotion Recognition | DeepFace |
| Text-to-Speech | Piper TTS |
| Operating System | Raspberry Pi OS |

## ⚙️ Hardware

- Raspberry Pi 5 (8 GB)
- Waveshare IMX219 8 MP Camera
- USB Microphone
- PCA9685 Servo Driver
- 2 × MG90S Servo Motors
- 2 × SG90 Servo Motors
- MAX98357A I2S Audio Amplifier
- 4 Ω 3 W Speaker
- Waveshare 2-inch LCD Display
- External regulated power supply

## 🔄 System Pipeline

Human Interaction
       │
       ├── Voice Input
       │       ↓
       │    Whisper
       │       ↓
       │    Ollama
       │       ↓
       │    AI Response
       │
       └── Visual Input
               ↓
           MediaPipe
               ↓
              dlib
               ↓
            DeepFace
               ↓
        Emotion Information
              ↓
        ┌───────────────┐
        │ Robot Control │
        └───────────────┘
          ↓      ↓      ↓
       Servo    LCD   Speaker
       Motion  Face    Audio
