<div align="center">

# Hey, I'm Pranes Kumar B 👋

### CSE (Big Data Analytics) • Full-Stack • IoT • Embedded Systems

**Building systems that connect the physical world to the cloud.**

<p>
  <a href="https://github.com/pranesdev">
    <img src="https://img.shields.io/github/followers/pranesdev?label=Followers&style=flat-square" />
  </a>
  <a href="https://github.com/pranesdev?tab=repositories">
    <img src="https://img.shields.io/badge/Projects-Explore-181717?style=flat-square&logo=github" />
  </a>
</p>

</div>

---

## 🧭 About Me

I'm a **Computer Science & Engineering student specializing in Big Data Analytics**, with a growing focus on building deployable, real-world systems. My work sits at the exact intersection of **Software → Hardware → Connectivity → Data → Cloud**. 

Rather than just building isolated applications, I enjoy engineering complete pipelines—from wiring microcontrollers and gathering sensor data to building the cloud architectures and front-end dashboards that make sense of it all.

*   🚢 **Currently Building:** [AEGIS](#-aegis---smart-maritime-boundary-detection-system), an offline-first Smart Maritime Boundary Detection System.
*   ⚡ **Hardware Focus:** ESP32, GPS, LoRa, Robotics, and Embedded Systems.
*   🌐 **Software Focus:** React, TypeScript, Node.js, and Data Science.
*   🧠 **Philosophy:** Turn real-world problems into practical, deployable systems. Build. Compete. Learn. Repeat.

---

## 🛠️ Tech Stack

### 💻 Languages & Frameworks
<p>
<img src="https://skillicons.dev/icons?i=cpp,python,java,kotlin,js,ts,react,nodejs,express,tailwind,html,css" />
</p>

### 📊 Data, Cloud & Tools
<p>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,docker,git,github" />
</p>

### ⚡ Hardware & Embedded
<p>
<img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

**Working With:** 
`ESP32` `LoRa` `GPS` `KiCad` `UART` `I²C` `SPI` `Socket.IO` `REST APIs` `SD Logging`

---

## 🚢 AEGIS - Smart Maritime Boundary Detection System

AEGIS is an **offline-first maritime safety ecosystem** designed to help fishermen maintain awareness of restricted maritime boundaries even when conventional internet connectivity is unavailable. 

### ⚙️ Architecture & Data Flow

```mermaid
flowchart LR

    BOAT["🚢 BOAT<br/><br/>ESP32 + GPS<br/>LoRa + OLED + SD"]
    LORA["📡 LoRa<br/><br/>433 MHz<br/>Long-Range Telemetry"]
    GATEWAY["🌊 COASTAL GATEWAY<br/><br/>LoRa Receiver<br/>Gateway Service"]
    CLOUD["☁️ CLOUD BACKEND<br/><br/>Node.js API<br/>Socket.IO"]
    DASH["🖥️ AUTHORITY DASHBOARD<br/><br/>Live Map<br/>Zones • Telemetry • Alerts"]

    BOAT -->|"Telemetry"| LORA
    LORA -->|"433 MHz"| GATEWAY
    GATEWAY -->|"HTTPS"| CLOUD
    CLOUD -->|"WebSocket"| DASH
