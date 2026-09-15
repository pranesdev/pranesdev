<div align="center">

# Hey, I'm Pranes Kumar B 👋

### CSE (Big Data Analytics) • Full-Stack Developer • IoT & Embedded Systems

<p>
Building systems that connect the physical world to the cloud.
</p>

</div>

---

## 🧭 About Me

I'm a Computer Science & Engineering student specializing in Big Data Analytics,
with a growing focus on **full-stack development, embedded systems and IoT**.

My interests sit at the intersection of:

**Software → Embedded Systems → IoT → Data → Cloud**

- 🚢 Building **AEGIS**, a Smart Maritime Boundary Detection System
- ⚡ Working with **ESP32, GPS, LoRa & embedded systems**
- 🌐 Building full-stack applications with **React, TypeScript & Node.js**
- 📊 Exploring **Data Science, Big Data & intelligent systems**
- 🤖 Exploring **Robotics and hardware engineering**
- 🧠 Interested in turning real-world problems into deployable systems

---

## 🛠️ Tech Stack

### Languages

<p>
<img src="https://skillicons.dev/icons?i=cpp,python,js,ts,java,kotlin" />
</p>

### Web & Backend

<p>
<img src="https://skillicons.dev/icons?i=react,nodejs,express,tailwind,html,css" />
</p>

### Data & Tools

<p>
<img src="https://skillicons.dev/icons?i=mongodb,postgres,docker,git,github" />
</p>

### Hardware & Embedded

<p>
<img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

**Also working with**

`ESP32` `LoRa` `GPS` `KiCad` `UART` `I²C` `SPI`
`Socket.IO` `REST APIs` `SD Logging`

---

# 🚢 Featured Project

<div align="center">

## AEGIS — Smart Maritime Boundary Detection System

### `Hardware → LoRa → Gateway → Cloud → Dashboard`

</div>

AEGIS is an **offline-first maritime safety system** designed to help fishermen
maintain awareness of restricted maritime boundaries even when conventional
internet connectivity is unavailable.

### ⚙️ Architecture

```text
┌──────────────────┐
│      BOAT        │
│                  │
│ ESP32            │
│  ├─ GPS          │
│  ├─ LoRa         │
│  ├─ OLED         │
│  └─ SD Blackbox  │
└────────┬─────────┘
         │
         │ 433 MHz LoRa
         ▼
┌──────────────────┐
│ Coastal Gateway  │
└────────┬─────────┘
         │
         │ HTTPS
         ▼
┌──────────────────┐
│   Node.js API    │
│   Socket.IO      │
└────────┬─────────┘
         │
         ▼
┌──────────────────┐
│ React Dashboard  │
│                  │
│ Live Boat Map    │
│ Boundary Zones   │
│ Telemetry        │
│ Alerts           │
└──────────────────┘

> **I don't just want to build applications. I want to build systems.**
