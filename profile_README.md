# Hey there, I'm Alan! 👋

I build things that sense, think, and act. Here's what I'm working on right now:

---

## 🌟 Featured Project: [SCARI](https://github.com/villaralan11/scari)

**Sistema de Clasificación Automática de Residuos Inteligente**

An intelligent waste-sorting bin that automatically classifies trash into **organic** vs **inorganic** using AI vision — built from scratch with ESP32-S3, ESP32-CAM, and the Groq API.

| | |
|---|---|
| 🤖 **AI** | llama-4-scout-17b-16e-instruct via Groq API (free tier) |
| 📷 **Vision** | ESP32-CAM → UART → ESP32-S3 (real-time JPEG streaming) |
| 🦾 **Actuation** | NEMA 17 stepper motor + A4988 driver (trapezoidal profile) |
| 💡 **Feedback** | Native RGB LED (WS2812) on GPIO48 |
| 🌐 **Portal** | Async web server with live dashboard + JSON API |
| 🔧 **Firmware** | Arduino IDE, FreeRTOS tasks, circular buffer logging |

**Dashboard Features:**
- Real-time classification stats (organic / inorganic / unknown)
- Accuracy gauge + distribution bars
- Full history with relative timestamps
- Captive portal (no internet needed)
- REST API endpoints (/status, /historial, /reset)

> _"The user just drops the trash — SCARI detects, classifies, and sorts it all by itself."_

---

## 🛠️ Tech Stack

C/C++ · Arduino · ESP32 · ESP32-S3 · ESP32-CAM · FreeRTOS · UART · I2C · SPI · Wi-Fi · HTTP/HTTPS · REST API · JSON · Computer Vision · AI/ML · IoT · Embedded Systems

---

## 📫 Connect with me

- 💼 Building cool embedded + AI projects
- 🌱 Currently learning more about edge AI and TinyML
- ⚡ Fun fact: I built a trash can that's smarter than my room organization

---

<div align="center">

**⭐ Check out [SCARI](https://github.com/villaralan11/scari) — my flagship project!**

</div>