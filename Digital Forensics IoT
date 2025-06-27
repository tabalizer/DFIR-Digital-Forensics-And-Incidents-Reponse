# 🌐 IoT Forensics Cheat Sheet 🧠📶  
**Based on SWGDE Best Practices for IoT Evidence – v1.0 (2022)**

---

## 🎯 1. Purpose & Audience
- 📌 On-scene **identification, seizure, and preservation** of Internet of Things (IoT) devices
- 👥 For: First responders, digital forensic analysts, attorneys, judges
- 🧩 Focus on *consumer-grade IoT devices* with onboard/internal storage

---

## 🧾 2. What is an IoT Device?
- 📡 Connected device that operates *without human interaction*
- 🔄 Uses: Wi-Fi, Bluetooth, Zigbee, Z-Wave, mobile data, proprietary protocols
- 🧬 Can contain **forensic artifacts**: logs, timestamps, user/device interactions

---

## 🔎 3. Identifying IoT Devices

### 👁️ Common Device Categories
- ⌚ **Wearables**: Smartwatches, shoes, fitness trackers, insulin pumps
- 📍 **Smart Tags**: AirTags, BLE/NFC/GPS tags, pet trackers
- 🔊 **Smart Speakers**: Alexa, Google Home
- 🖥️ **Smart Displays**: Echo Show, Google Nest Hub
- 🛰️ **Sensors**: Motion, temperature, humidity, vibration, gas
- 🔧 **Control Systems**: Thermostats, actuators, smart locks
- 📷 **Capture Devices**: Cameras, smart doorbells, ATMs, card skimmers
- 💉 **Implants**: RFID/NFC modules, cochlear, pacemakers
- 🚗 **Vehicles**: Infotainment, telematics, drones
- 🍳 **Appliances**: TVs, fridges, vacuums, washers, coffee machines

### 🗣️ Wake Words (Defaults)
- **Alexa** → "Alexa"
- **Google Home** → "Hey Google"
- **Apple Siri** → "Hey Siri"
- **Facebook Portal** → "Hey Portal"

---

## 🧰 4. Tools & Discovery Techniques
- 🔍 Wireless scans: Wi-Fi, Bluetooth, Zigbee, Z-Wave, LTE
- 🛠️ Tools: Fing, Redfang (Kali), Kismet
- 🔄 Router reboot: Can reveal hidden connections
- 🕸️ Note: Mesh networks may relay through "hops"

---

## 📦 5. Collection Best Practices

### 📝 Pre-Seizure Documentation
- 📸 Take pictures of:
  - Display/status indicators
  - Device condition
  - Serial numbers, MAC address
- 🔗 Document network topology and connected devices

### 🛑 Trigger Event Risks
- 🗣️ Wake word spoken
- 🎛️ Switch flipped
- 🎵 Loud noise
- 🔌 Unplugging/disconnecting
- ⚠️ Could cause: log updates, alerts, or *data deletion*

### 📡 Isolation Techniques
- 🔌 Unplug/remove battery
- 🧲 Use Faraday bag (⚠️ Don’t place battery inside!)
- 🔌 Power off at **circuit breaker** if hardwired
- 🌐 Disconnect network/internet access (cables, APs, routers)

---

## 🛡️ 6. Preservation Guidelines

- ⚠️ Ensure **complete network and power isolation**
- 🔋 Remove battery *if possible* (some embedded batteries require full disassembly)
- 📦 Store in non-conductive, signal-blocking packaging
- 📨 Send **preservation notices** to cloud providers *ASAP*

---

## 🧩 7. Artifact Categories

| Category      | Examples |
|---------------|----------|
| 📁 Local Logs  | Wake times, device pairing, commands issued |
| 📍 Location    | Connection to mobile device, geolocation logs |
| 📡 Network     | SSIDs, MAC addresses, mesh hops |
| 🔗 Cross-Linked | Triggered IFTTT events, smart-home chain reactions |
| 🛑 Volatile     | RAM-stored logs may be lost on power-off |

---

## 🧠 8. Challenges & Considerations

- ❗ Tool availability is limited
- 🔒 Encrypted/proprietary storage formats
- 🔗 Distributed data: device ↔ app ↔ cloud
- 🧬 Biological risk: wearables may contain DNA, pathogens
- 🎥 Live audio/video recording risk: could alert suspect or misrecord statements
- ⚙️ Devices may be booby-trapped or intentionally misleading

---

## 📚 9. Reference Resources

- 🔬 [NIST CFReDS](https://www.nist.gov/programs-projects/computer-forensic-reference-data-sets)
- 🧬 [Artifact Genome Project – Univ. of New Haven](https://agp.newhaven.edu/)
- 🛠️ [SWGDE Best Practices Collection Page](https://www.swgde.org/documents)

---

🧾 **TIP:** Treat IoT like mobile devices—assume paired systems, ephemeral logs, and cloud backups. Isolate and document **before interacting.**
