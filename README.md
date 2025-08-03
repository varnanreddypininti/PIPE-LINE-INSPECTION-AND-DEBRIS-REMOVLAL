# 🤖 Manhole Inspection & Debris Removal Robot

A semi-autonomous robotic system designed to **inspect hazardous manholes**, **detect toxic gases**, and **remove blockages**—improving worker safety and operational efficiency in urban infrastructure maintenance.

---

## 🔍 Project Overview

Manual manhole inspection poses serious risks due to toxic gas buildup, debris, and physical inaccessibility. This project introduces a **remote-controlled robot** equipped with an **ESP32-CAM**, **gas sensors**, and a **robotic arm** to safely perform surveillance and clean-up operations.

---

## 🧠 Features

- 📷 **Live Video Feed** via ESP32-CAM
- 💨 **Gas Detection** using MQ-series sensors
- 🦾 **Debris Removal** with robotic arm
- 📱 **Remote Control** via Blynk IoT mobile app
- 🔋 **Portable Power Supply** for on-field use

---

## ⚙️ Hardware Components

| Component           | Function                            |
|--------------------|-------------------------------------|
| ESP32-CAM          | Live video streaming                |
| Arduino Mega       | Core control (optional if not ESP-only) |
| MQ-x Gas Sensors   | Detection of harmful gases          |
| Robotic Arm        | Manual debris removal               |
| DC Motors          | Navigation and movement             |
| Blynk IoT          | Smartphone control interface        |
| Battery Pack       | Power source                        |

---

## 🚀 Getting Started

### 🧑‍💻 Prerequisites

- Arduino IDE
- Blynk App (create a new project and get your Auth Token)
- ESP32 board drivers

### 🛠️ Steps

1. Open `manhole_robot.ino` in Arduino IDE.
2. Enter your **WiFi credentials** and **Blynk Auth Token**.
3. Upload to ESP32/Arduino board.
4. Power the robot and control via the Blynk App.

---

## 🛡️ Applications

- Underground pipeline and sewer inspection
- Toxic gas detection in confined spaces
- Industrial maintenance tasks
- Municipal safety operations

---


## 👤 Author

- **Varnan Reddy Pininti**  
  Robotics Club – SNIST  
---

> 🛠 Empowering Smart Urban Safety with Robotics & IoT!
