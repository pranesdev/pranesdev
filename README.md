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

I'm a **Computer Science & Engineering student specializing in Big Data Analytics**,
with a growing focus on **embedded systems, IoT, full-stack development and data**.

My interests sit at the intersection of:

**Software → Hardware → Connectivity → Data → Cloud**

- 🚢 Building **AEGIS**, a Smart Maritime Boundary Detection System
- ⚡ Working with **ESP32, GPS, LoRa & embedded systems**
- 🌐 Building full-stack applications with **React, TypeScript & Node.js**
- 📊 Exploring **Data Science, Big Data & intelligent systems**
- 🤖 Exploring **Robotics and hardware engineering**
- 🧠 Turning real-world problems into practical, deployable systems

> **I don't just want to build applications. I want to build systems.**

---

## 🛠️ Tech Stack

### 💻 Software & Languages

<p>
<img src="https://skillicons.dev/icons?i=cpp,python,js,ts,java,kotlin" />
</p>

### 🌐 Web & Backend

<p>
<img src="https://skillicons.dev/icons?i=react,nodejs,express,tailwind,html,css" />
</p>

### 📊 Data & Development Tools

<p>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,docker,git,github" />
</p>

### ⚡ Hardware & Embedded

<p>
<img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

**Also working with**

`ESP32` `LoRa` `GPS` `KiCad` `UART` `I²C` `SPI`  
`Socket.IO` `REST APIs` `SD Logging`

---

# 🚢 AEGIS

<div align="center">

## Smart Maritime Boundary Detection System

### `Hardware → LoRa → Gateway → Cloud → Dashboard`

</div>

AEGIS is an **offline-first maritime safety system** designed to help fishermen
maintain awareness of restricted maritime boundaries even when conventional
internet connectivity is unavailable.

### ⚙️ How AEGIS Works

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

### 🔩 Inside the Boat

| Component | Role |
|:---|:---|
| 🛰️ **NEO-6M GPS** | Real-time position tracking |
| ⚡ **ESP32** | Processing & system control |
| 📡 **SX1278 LoRa** | Long-range telemetry |
| 📟 **OLED Display** | Local system status & alerts |
| 💾 **MicroSD** | Offline blackbox telemetry logging |

### 🔄 Data Flow

<div align="center">

**GPS → ESP32 → LoRa → Gateway → Node.js → Socket.IO → Dashboard**

</div>

AEGIS follows an **offline-first architecture**: the boat can continue
detecting boundaries and recording telemetry even when internet connectivity
is unavailable.

### ✨ Key Features

- 📡 Long-range **LoRa telemetry**
- 🛰️ GPS-based maritime boundary detection
- 📴 **Offline-first** operation
- 💾 SD-card **blackbox logging**
- 🚨 Safe / Warning / Danger zone awareness
- 🗺️ Real-time coastal authority dashboard
- 📱 Android companion application
- 🔌 Hardware-to-cloud communication pipeline

### 🏆 AEGIS Recognition

**🏅 DevFest '26 — 4th Place, IoT Domain**

**🥈 PARALLAX '26 — 2nd Place, Hardware Track**

**💰 PARALLAX '26 — ₹8,000 Cash Prize**

<div align="center">

<a href="https://github.com/pranesdev/Aegis-Maritime-System">
<img src="https://img.shields.io/badge/Explore%20AEGIS-181717?style=for-the-badge&logo=github" />
</a>

</div>

---

# 🚀 Other Projects

<table>
<tr>

<td width="50%">

### 🌊 AEGIS Frontend

Real-time maritime monitoring dashboard for boat telemetry,
boundary awareness and system visualization.

**TypeScript • React**

<a href="https://github.com/pranesdev/aegis-frontend">
View Repository →
</a>

</td>

<td width="50%">

### 📱 AEGIS Fisherman App

Mobile companion application designed as part of the
AEGIS maritime safety ecosystem.

**Kotlin • Android**

<a href="https://github.com/pranesdev/aegis-fisherman-app">
View Repository →
</a>

</td>

</tr>

<tr>

<td width="50%">

### 🇯🇵 Japanese

Interactive platform for learning Japanese fundamentals,
grammar, kana and kanji.

**HTML • JavaScript**

<a href="https://github.com/pranesdev/Japanese">
View Repository →
</a>

</td>

<td width="50%">

### 🔬 More Experiments

Exploring software, embedded systems, data and hardware
through continuous projects and prototypes.

**C++ • Python • IoT • Data**

</td>

</tr>
</table>

---

# 🏆 Achievements & Recognition

<div align="center">

### 🥇 COMPETITION HIGHLIGHTS

<img src="https://img.shields.io/badge/DevFest_'26-4th%20Place%20%7C%20IoT%20Domain-181717?style=for-the-badge" />

<img src="https://img.shields.io/badge/PARALLAX_'26-2nd%20Place%20%7C%20Hardware%20Track-181717?style=for-the-badge" />

<img src="https://img.shields.io/badge/PARALLAX_'26-₹8%2C000%20Cash%20Prize-181717?style=for-the-badge" />

<br><br>

### 🎓 ACADEMIC RECOGNITION

<img src="https://img.shields.io/badge/SRM%20Project%20Expo-Selected%20to%20Present-181717?style=for-the-badge" />

<br><br>

### 🔥 PROJECT RECOGNITION

<img src="https://img.shields.io/badge/DSC%20SRM%20IST-Consecutive%20Hackathon%20Winner-181717?style=for-the-badge" />

</div>

---

# 🧠 Current Direction

```text
                         SOFTWARE
                            │
                            ▼
                    ┌───────────────┐
                    │ IoT & Embedded│
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ Connectivity  │
                    │ LoRa • APIs   │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │ Data & Cloud  │
                    └───────┬───────┘
                            │
                            ▼
                    REAL-WORLD SYSTEMS
```

### Currently exploring

`Embedded Systems` · `IoT` · `Robotics` · `Data Science`  
`Big Data` · `System Design` · `Hardware-to-Cloud`

---

# 🌟 What's Next

- 🎓 Selected to present a project at **SRM Project Expo**
- 🏛️ Upcoming opportunity to **meet the Chairman of SRM IST**
- 🚀 Continuing to develop and compete with **AEGIS**
- ⚡ Going deeper into **embedded systems, robotics and IoT**

> **Build. Compete. Learn. Repeat.**

---

<div align="center">

## ⚡ From bits to boards, from boards to the cloud.

<br>

<a href="mailto:praneskumarb01@gmail.com">
<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://github.com/pranesdev">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=pranesdev&label=Profile%20Views&style=flat-square" />

</div>
