## 👁️ GuardianEye – Smart Eyewear for the Visually Impaired

> An AI-powered, sensor-integrated wearable device for obstacle detection, text recognition, navigation, and real-time assistance—built to empower visually impaired individuals with safe, independent mobility.

---

![GuardianEye Banner](https://img.shields.io/badge/Smart-Wearable-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Status](https://img.shields.io/badge/status-Prototype-orange)

## 🔍 Overview

**GuardianEye** is a multi-sensory smart eyewear system designed to assist visually impaired individuals in navigating their surroundings confidently and independently. By combining advanced **AI**, **computer vision**, and **sensor fusion**, the device offers:

- Real-time **obstacle detection**
- **Currency note recognition**
- **Printed text reading** via OCR
- **Multi-language voice feedback**
- Location tracking for caregivers
- Hands-free voice command control
- **Emergency alert** system with haptic and audio feedback

---

## 🚀 Key Features

| Feature                        | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 🛣️ Real-Time Obstacle Detection | Detects and classifies static/dynamic obstacles using **LiDAR + YOLO**     |
| 💬 Multi-Language Voice Output | NLP-based output in **multiple languages** for localized interaction        |
| 📷 Optical Character Recognition (OCR) | Reads text from newspapers, signboards, etc., and converts to speech |
| 🎙️ Voice Command System        | Microphone-powered **hands-free interaction** via natural language          |
| 💸 Currency Note Detection     | Identifies denomination using computer vision to prevent fraud             |
| 🧭 GPS Location Tracking       | Enables **family members** to track user’s location remotely                |
| 🤖 Person & Object Recognition | Recognizes known individuals and frequently seen objects                    |
| 📳 Haptic Feedback             | Vibrates for obstacle alerts, turns, or important environmental cues       |
| 🚨 Emergency Beep Alert       | Loud **beeping sound** triggers when immediate danger is detected          |

---

## 🧠 Technologies Used

- **🧠 AI Models:** YOLOv8 (Object Detection), Tesseract (OCR), NLP (Speech-to-Text / Text-to-Speech)
- **🌐 Communication:** Bluetooth Low Energy (BLE)
- **🔊 Audio Feedback:** Bone conduction speakers
- **📷 Sensors:** LiDAR, Pi camera, GPS
- **📦 Hardware Platform:** Microcontroller (Raspberry Pi), Rechargeable battery, Microphone

---

## 🧰 System Architecture

```

User Commands ──► Microphone
│
┌──────────────▼──────────────┐
│      AI Processing Unit     │
│  (YOLO, OCR, NLP, Sensor Fusion) │
└──────────────┬──────────────┘
│
┌──────────────┐   ┌───────────────┐   ┌───────────────┐
│ LiDAR Sensor │   │  Camera       │   │  GPS Module   │
└────┬─────────┘   └────┬──────────┘   └────┬──────────┘
▼                  ▼                  ▼
Real-Time Obstacle   Text Recognition   Location Tracking
Detection & Feedback  + Object ID       + Caregiver Alert

Output:
🔊 Voice Feedback (Multi-Language, TTS)
📳 Haptic Vibrations
🚨 Emergency Beep Alert

```

---

## 🎯 Use Cases

- Navigate urban streets, stairs, and corridors
- Recognize people at work or home
- Read public signs or packaging labels
- Detect currency during monetary exchange
- Alert surroundings in case of emergencies
- Stay connected with caregivers for safety

---

## 📷 Media & Demos

> Coming Soon: Demo Video 

- ✅ Real-time object detection
- ✅ Text-to-speech conversion of printed material
- ✅ GPS tracking dashboard for caregivers
- ✅ Voice-command feature demo

---

## 🧪 Project Status

- [x] Research and literature review
- [x] Hardware component selection
- [x] AI module prototyping (YOLO + OCR)
- [x] NLP-based multi-language system
- [ ] Integration & Testing
- [ ] Real-world trials with visually impaired users
- [ ] Final production and optimization

---


## 👨‍💻 Contributors

- **Anirudh Garg** – Computer vision(Team Lead)
- **Aaradhya Sharma** – Computer vision 
- **Abhiroop Singh** – IoT 
- **Rajveer Singh** – Speech Processing, Documentation  
- **Bhavneet Kaur** – NLP, Speech Processing 

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Support & Contact

Have feedback, ideas, or want to collaborate? Reach out at:

📧 agarg3_be22@thapar.edu  
🌐 [Thapar Institute of Engineering & Technology](https://www.thapar.edu)

---

> _"Let’s build a world where everyone can see possibilities—even without sight."_ 🌍
