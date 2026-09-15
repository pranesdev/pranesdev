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

---

# 🏆 Achievements

<div align="center">

### 🥇 COMPETITION HIGHLIGHTS

<img src="https://img.shields.io/badge/DevFest_'26-4th%20Place%20%7C%20IoT-181717?style=for-the-badge" />
<img src="https://img.shields.io/badge/PARALLAX_'26-2nd%20Place%20%7C%20Hardware-181717?style=for-the-badge" />
<img src="https://img.shields.io/badge/PARALLAX_'26-₹8%2C000%20Cash%20Prize-181717?style=for-the-badge" />

<br><br>

### 🎓 ACADEMIC RECOGNITION

<img src="https://img.shields.io/badge/SRM%20Project%20Expo-Selected%20to%20Present-181717?style=for-the-badge" />

<br><br>

### 🔥 PROJECT RECOGNITION

<img src="https://img.shields.io/badge/DSC%20SRM%20IST-Consecutive%20Hackathon%20Winner-181717?style=for-the-badge" />

</div>

---

### 🌟 What's Next

Currently taking my projects beyond hackathons and into larger platforms —
with an upcoming opportunity to **meet the Chairman of SRM IST** and present
my work.

> **From building prototypes to building systems that get recognized.**

- 🚢 Building **AEGIS**, a Smart Maritime Boundary Detection System
- ⚡ Working with **ESP32, GPS, LoRa & embedded systems**
- 🌐 Building full-stack applications with **React, TypeScript & Node.js**
- 📊 Exploring **Data Science, Big Data & intelligent systems**
- 🤖 Exploring **Robotics and hardware engineering**
- 🧠 Interested in turning real-world problems into deployable systems

> **I don't just want to build applications. I want to build systems.**

---

## 🛠️ Tech Stack

### 💻 Software

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

### ⚙️ System Architecture

### ⚙️ System Architecture

```mermaid
flowchart LR

    subgraph BOAT["🚢 BOAT — Edge Device"]
        GPS["🛰️ GPS<br/>NEO-6M"]
        ESP["⚡ ESP32<br/>Controller"]
        LORA["📡 LoRa<br/>433 MHz"]
        OLED["📟 OLED<br/>Status"]
        SD["💾 SD Card<br/>Blackbox"]

        GPS --> ESP
        ESP --> OLED
        ESP --> SD
        ESP --> LORA
    end

    subgraph GATEWAY["📡 COASTAL GATEWAY"]
        RX["LoRa Receiver"]
        GW["Gateway Service"]
        RX --> GW
    end

    subgraph CLOUD["☁️ CLOUD"]
        API["Node.js API"]
        SOCKET["Socket.IO"]
        DB[("MongoDB")]

        API --> SOCKET
        API --> DB
    end

    subgraph DASH["🖥️ AUTHORITY DASHBOARD"]
        MAP["Live Boat Map"]
        ZONES["Boundary Zones"]
        TEL["Telemetry"]
        ALERT["Alerts"]
    end

    LORA -->|"433 MHz LoRa"| RX
    GW -->|"HTTPS"| API
    SOCKET -->|"WebSocket"| MAP
    SOCKET --> ZONES
    SOCKET --> TEL
    SOCKET --> ALERT
```
