<div align="center">

# Hey, I'm Pranes Kumar B 👋

### CSE (Big Data Analytics) • Full-Stack • IoT • Embedded Systems

**Engineering the bridge between physical sensors and cloud intelligence.**

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

I am a **Computer Science & Engineering student specializing in Big Data Analytics**, focused on building deployable, mission-critical systems. My expertise lies at the intersection of **Hardware → Firmware → Connectivity → Cloud**.

Rather than building isolated apps, I engineer end-to-end pipelines: from designing PCBs and implementing low-level firmware to architecting scalable cloud backends and real-time dashboards.

*   🚢 **Currently Engineering:** [AEGIS](#-aegis---smart-maritime-boundary-detection-system), a predictive, self-healing maritime safety ecosystem.
*   ⚡ **Embedded Focus:** RTOS, ESP32, LoRa Mesh, GPS, and Sensor Fusion.
*   🌐 **Software Focus:** TypeScript, React, Node.js, and Distributed Systems.
*   🧠 **Philosophy:** Solve real-world constraints with engineering rigor. Build. Validate. Optimize. Repeat.

---

## 🛠️ Tech Stack

### 💻 Software & Cloud
<p>
<img src="https://skillicons.dev/icons?i=cpp,python,java,kotlin,js,ts,react,nodejs,express,tailwind,html,css,mongodb,postgres,docker,git,github" />
</p>

### ⚡ Hardware & Embedded
<p>
<img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

**Deep Dive:**
`ESP32` `LoRa` `GPS` `KiCad` `UART` `I²C` `SPI` `Socket.IO` `REST APIs` `SD Logging` `ESP-NOW`

**Algorithmic Implementations:**
`PMA* Routing` `EWMA` `Welford's Online Algorithm` `HMAC Auth` `Binary Packet Serialization`

---

## 🚢 AEGIS - Smart Maritime Boundary Detection System

AEGIS is an **offline-first maritime safety ecosystem** designed to prevent small-scale fishermen in the Palk Strait from unintentionally crossing the International Maritime Boundary Line (IMBL).

### ⚙️ Architecture: Predictive Self-Healing Mesh

AEGIS has evolved from a simple telemetry link to a **Predictive Self-Healing Mesh Network**, ensuring that safety alerts and telemetry reach the coast even in volatile marine environments.

```mermaid
flowchart LR
    subgraph MeshNetwork [Maritime Mesh Network]
        B1["🚢 Boat Node A"] --- B2["🚢 Boat Node B"]
        B2 --- B3["🚢 Boat Node C"]
        B1 --- B3
        B3 --- GW["🌊 Coastal Gateway"]
    end

    GW -->|"HTTPS/JSON"| CLOUD["☁️ Cloud Backend"]
    CLOUD -->|"WebSocket"| DASH["🖥️ Authority Dashboard"]

    B1 -.->|"Offline Geofencing"| ALERTS["🚨 Local Alerts"]
