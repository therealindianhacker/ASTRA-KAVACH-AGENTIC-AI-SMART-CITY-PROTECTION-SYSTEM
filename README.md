# 🛡️ ASTRA KAVACH – Agentic AI Watch

### AI-Powered Cybersecurity & Physical Threat Protection System

**Founder:** Subhampreet Singh
**Team:** Quantum Hackers
**Project Type:** Agentic AI + Embedded + Cybersecurity + IoT
**Status:** Production-Ready | Hackathon-Ready | Scalable

---

# 📖 Overview

**ASTRA KAVACH** is an advanced **Agentic AI-powered wearable security platform** designed to protect users from:

* Cyber threats
* Wireless attacks
* Unauthorized access
* Physical threats
* Surveillance risks

It integrates **ESP32 hardware, AI voice intelligence, VPS cloud backend, and Telegram command control** into a single unified security ecosystem.

ASTRA KAVACH acts as an **autonomous digital bodyguard.**

---

# ⚡ Core Features

## 🤖 AI Agent Features

* Agentic AI decision-making
* Autonomous threat detection
* Voice interaction (ElevenLabs integration ready)
* Intelligent alert system

---

## 📡 Cybersecurity Protection

* WiFi threat monitoring
* Bluetooth environment awareness
* Signal intelligence logging
* Remote command execution

---

## 🌍 Cloud Connectivity

* Real-time VPS communication
* Live telemetry monitoring
* Secure API architecture
* Remote control capability

---

## 📱 Telegram Control Center

Control your device remotely:

Commands:

```
/status
/logs
/gps
/restart
/alert
```

---

## 🖥️ Live Dashboard

Features:

* Real-time logs
* GPS tracking
* Device status
* Threat monitoring

Deployable on:

* Netlify
* VPS
* Local server

---

## 📷 Hardware Expansion Support

Supports integration with:

* ESP32-CAM
* GPS Module
* Microphone
* Camera
* Sensors
* SDR modules

---

# 🧠 System Architecture

```
                ┌───────────────┐
                │ ASTRA KAVACH  │
                │ ESP32 Watch   │
                └──────┬────────┘
                       │
                       ▼
                ┌───────────────┐
                │ VPS Cloud     │
                │ Backend       │
                └──────┬────────┘
                       │
       ┌───────────────┼───────────────┐
       ▼               ▼               ▼
 Telegram Bot     Web Dashboard      AI Voice
 Control          Monitoring         Assistant
```

---

# 📁 Repository Structure

```
astra-kavach-ai-watch/

firmware/
backend/
telegram/
dashboard/
ai/
hardware/
docs/

README.md
LICENSE
```

---

# ⚙️ Installation Guide

---

# 1️⃣ VPS Backend Setup

Install dependencies:

```
sudo apt update
sudo apt install python3 python3-pip
pip install flask
```

Run server:

```
python server.py
```

---

# 2️⃣ Telegram Bot Setup

Create bot via:

@BotFather

Edit:

```
telegram/bot.py
```

Add:

```
TOKEN="YOUR_TOKEN"
```

Run:

```
python bot.py
```

---

# 3️⃣ Dashboard Setup

Deploy:

```
dashboard/
```

On:

* Netlify
* VPS
* Localhost

---

# 4️⃣ ESP32 Firmware Setup

Open:

```
firmware/esp32_watch/
```

Edit:

```
WiFi Name
WiFi Password
VPS IP
```

Upload using Arduino IDE.

---

# 🔐 Security Features

* Remote monitoring
* Secure communication ready
* Expandable encryption support
* Modular architecture

---

# 🧠 AI Integration

Supports:

* ElevenLabs
* OpenAI
* Offline AI engines

Voice Assistant Capabilities:

* Speak alerts
* Respond to commands
* Provide intelligence updates

---

# 🚀 Hackathon Ready

This project satisfies hackathon requirements:

✔ Working prototype
✔ Functional deployment
✔ Innovation
✔ Real-world use case
✔ Technical depth

---

# 🧪 API Endpoints

Backend APIs:

```
POST /log
POST /gps
POST /camera
GET /all
```

---

# 📡 Example Data

```
{
 "device": "astra_watch",
 "status": "active",
 "threat": "none"
}
```

---

# 🛠️ Technology Stack

Hardware:

* ESP32
* ESP32-CAM
* GPS Module

Software:

* Python
* Flask
* Arduino

Cloud:

* VPS
* Netlify

AI:

* ElevenLabs
* Agentic AI architecture

---

# 🔮 Future Roadmap

Planned Features:

* Mobile app
* End-to-end encryption
* OTA firmware updates
* Live video streaming
* Autonomous defense mode

---

# 👨‍💻 Author

Subhampreet Singh
Cybersecurity Researcher
Embedded Systems Developer
Agentic AI Engineer

---

# ⚠️ Legal Disclaimer

This project is intended for:

* Educational use
* Research purposes
* Ethical security development

Do not use for illegal activities.

---

# 📜 License

MIT License

---

# ⭐ Support the Project

If you like this project:

Star ⭐ the repo
Fork 🍴 the repo
Contribute 🤝

---

# 🛡️ ASTRA KAVACH

**Your Safety is My Responsibility**
