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
```

### ✨ Key Features
*   **Hardware Stack:** NEO-6M GPS for position tracking, ESP32 for processing, and SX1278 LoRa for long-range telemetry.
*   **Offline-First:** Boats can detect boundaries and record blackbox telemetry to a MicroSD card without an internet connection.
*   **Live Dashboard:** Real-time authority dashboard mapping safe, warning, and danger zones.

<div align="center">
<a href="https://github.com/pranesdev/Aegis-Maritime-System">
<img src="https://img.shields.io/badge/Explore%20AEGIS%20Repository-181717?style=for-the-badge&logo=github" />
</a>
</div>

---

## 🚀 Other Projects

<table>
<tr>
<td width="50%">

### 🌊 AEGIS Frontend
Real-time maritime monitoring dashboard for boat telemetry, boundary awareness and system visualization.
*TypeScript • React*
<br><a href="https://github.com/pranesdev/aegis-frontend">View Repository →</a>
</td>

<td width="50%">

### 📱 AEGIS Fisherman App
Mobile companion application designed as part of the AEGIS maritime safety ecosystem.
*Kotlin • Android*
<br><a href="https://github.com/pranesdev/aegis-fisherman-app">View Repository →</a>
</td>
</tr>

<tr>
<td width="50%">

### 🇯🇵 Japanese Learner
Interactive platform for learning Japanese fundamentals, grammar, kana, and kanji.
*HTML • JavaScript*
<br><a href="https://github.com/pranesdev/Japanese">View Repository →</a>
</td>

<td width="50%">

### 🔬 Hardware Experiments
Exploring software, embedded systems, data, and hardware through continuous micro-projects and prototypes.
*C++ • Python • IoT*
</td>
</tr>
</table>

---

## 🏆 Milestones & Achievements

*   **PARALLAX '26:** 🥈 2nd Place in Hardware Track (₹8,000 Cash Prize) for AEGIS.
*   **DevFest '26:** 🏅 4th Place in the IoT Domain for AEGIS.
*   **DSC SRM IST:** 🔥 Consecutive Hackathon Winner.
*   **SRM Project Expo:** 🎓 Selected to present AEGIS, leading to an upcoming opportunity to meet the Chairman of SRM IST.

---

<div align="center">

## ⚡ From bits to boards, from boards to the cloud.

<br>

<a href="mailto:praneskumarb01@gmail.com
">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/pranesdev">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=pranesdev&label=Profile%20Views&style=flat-square" />

</div>
