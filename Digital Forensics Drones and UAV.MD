# 🛸 Drone Forensics Cheat Sheet 🧠📡  
**Based on SWGDE Best Practices v1.0 – Jan 2022**

---

## 🎯 1. Purpose & Scope
- 📌 Focused on **small Unmanned Aerial Systems (sUAS)** used for flight (not ground or water)
- 👤 For field personnel & digital forensic examiners
- 🎯 Applies to **commercial and consumer drones**

---

## 🚨 2. Device Seizure & Safety

### 🛑 Safety Concerns
- ⚠️ Propellers = Dangerous. Spin-up risk = ⚙️ high RPMs
- 🔒 Power off if possible, else:
  - 🥅 Use blanket/net to stop propellers
  - 🔄 Turn upside down to disable sensors
- 🔋 **LiPo batteries** are volatile—store in fireproof containers
- 🧤 Wear gloves for damaged battery handling

### 📦 Evidence Collection Checklist
- 🔌 Power state (on/off)
- 🧱 Physical condition, visible damage
- 🆔 Serial/Model #, FAA registration
- 📡 Payloads/mods (hazards, weapons?)
- 📶 Nearby devices (phones, controllers, laptops)
- 🧭 GPS collection coordinates
- 🛣️ Observed flight path/target
- 📷 Make/model of attached camera
- 🔗 Seize synced devices (e.g., phone, tablet, controller)
- 📦 Transport in Faraday bag or remove battery
- 📸 Document scene + actions

---

## 💾 3. Data Acquisition Techniques

### 🔍 Methods
- 🧩 Logical: USB, Wi-Fi, app interface
- 🪛 Invasive: ISP, Chip-Off (eMMC, NAND, etc.)
- 🧠 Choice depends on: examiner skill, device condition, goals

### 📂 Evidence Sources
- 💽 SD/microSD Cards: External or onboard, often in gimbal/camera
- 🖧 PCBs: May need chip-off, be cautious of underfill/coating
- 🔄 Synced Devices: May store logs/media (phones, tablets, etc.)
- ☁️ Cloud Accounts: DJI, Parrot, etc. may store:
  - Media
  - Flight logs
  - Social uploads

---

## 🧩 4. Potential Artifacts

### 📸 User-Created
- Photos/videos/audio
- Custom waypoints or flight paths

### 🧭 User-Activity
- 🗓️ Dates/times of flight
- 📍 GPS logs, altitude, direction
- 🛬 Launch/landing sites
- 📁 Config files
- 🎯 Mission-specific data

### ⚙️ Operating/System
- FAA Reg. Number
- Device pairings (e.g., phones, batteries, controllers)
- Software/firmware versions

---

## 🔎 5. Data Analysis 🔬

- 🛠️ Use primary & secondary tools for validation
- 🧪 Test tools against known datasets (e.g., NIST CFReDS)
- 💻 Understand OS/filesystem (Linux, UNIX, Android)
- 📉 Limited tools for raw physical partitions → flight log parsers may help
- ✅ Apply traditional forensic principles (just like HDD/mobiles)

---

## ⚠️ 6. Caveats & Risks

### ⏳ Volatile Data
- ⚠️ Some drones overwrite flight logs when full
- 📴 Don’t power ON if not needed!

### 💥 Remote Wipe
- Treat as internet-capable → Isolate!
- 🧲 Faraday bag or battery removal if large

### 🔐 Encryption
- Encrypted logs (DAT) → some tools may not parse without vendor support

### 📍 GPS Accuracy
- 🛰️ Calibration issues may cause errors
- ✅ Cross-validate with:
  - Photos/video context
  - Recovery location
  - Sync'd devices
  - Satellite count at log time

---

## 📚 7. Key Resources

### 🔗 External
- [Interpol Drone Incident Framework (2020)](https://www.interpol.int/content/download/15298/file/DFL_DroneIncident_Final_EN.pdf)
- [DHS Drone Forensics Program](https://www.dhs.gov/science-and-technology)
- [FAA UAS Portal](https://www.faa.gov/uas)

### 📄 Related SWGDE Docs
- Best Practices for:
  - 📱 Mobile Device Evidence
  - 🧪 Chip-Off
  - 📲 Mobile Device Forensics
  - 🔍 Digital Video Analysis
- 📦 Acquisition of Novel Devices
- ✅ Tool Testing Requirements

---

## 📖 Definitions

- **Small UAS** = Drone < 55 lbs with all onboard components
- **System** = Aircraft + controller + communication/control components

---

🛑 **Reminder:** Always document thoroughly, isolate devices, and confirm tool validation. Drone forensics is evolving—stay updated!
