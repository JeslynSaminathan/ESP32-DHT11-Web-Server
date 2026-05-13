# 🌡️ ESP32 IoT Weather Station Dashboard ☁️

A professional-grade real-time environmental monitoring system that serves a live, responsive web interface directly from an ESP32 microcontroller.

---

## 📺 Project Demonstration 🎥
![ESP32 Weather Station](esp32%20weather%20station.mp4)

> *Note: If the video doesn't play automatically in your browser, click the link above to view the live demonstration.*

---

## 🚀 Overview 🌐
This project integrates hardware and software to create a localized IoT solution. The ESP32 acts as both a data processor and a web server, reading environmental variables from a DHT11 sensor and rendering them on a custom HTML/CSS dashboard accessible via a local IP address.

## 🛠️ Hardware Stack ⚙️
* **Microcontroller:** ESP32 DevKit V1 🧠
* **Sensor:** DHT11 (Temperature & Humidity) 🌡️
* **Connectivity:** 2.4GHz Wi-Fi 📶
* **Wiring Setup:** 🔴 **VCC** -> 3.3V
    * ⚫ **GND** -> GND
    * 🟡 **DATA** -> GPIO 26

---

## 💻 Software & Libraries 📚
The following libraries are utilized in this project:
* **DHT Sensor Library** (Adafruit)
* **Adafruit Unified Sensor** (Dependency)
* **WiFi & WebServer** (Standard ESP32 Core)

## 🔧 Installation & Usage 🛠️
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/grabimayo/ESP32-DHT11-Web-Server.git](https://github.com/grabimayo/ESP32-DHT11-Web-Server.git)
