# 🧾 Digital Forensics Cheat Sheet 📱💻  
**Focus: Mobile Device Evidence | SWGDE v1.2 (2020)**

---

## 🧭 1. Planning & Preparation
- 🧰 **Prepare Gear**: Chargers, Faraday bags, tools, cables, write-blockers
- 🛂 **Legal Authority**: Confirm search warrant, consent, or legal justification
- 📋 **Triage Decision**: Field analysis ≠ Full forensic exam

---

## 📸 2. Documentation 🖊️
- 🖼️ **Scene Photos**: Document device, peripherals, display state
- 🧾 **Evidence Notes**: Device make/model, serials, passcode status
- 🔗 **Chain of Custody**: Record all handling w/ names, timestamps

---

## 🔒 3. Preservation 🛡️
### iOS Devices 🍏
- 🔌 Keep device powered ON
- ✈️ Enable *Airplane Mode* → Turn off WiFi/Bluetooth
- ⚡ Keep connected to power (in Faraday bag!)
- ❌ If off → **Do NOT power on**
- ⏳ Extend Auto-lock, prevent screen timeout

### Android Devices 🤖
- 🔌 Keep powered ON, maintain charge
- ✈️ Enable *Airplane Mode* and disable wireless manually
- ⚙️ Enable USB Debugging if possible
- 🔍 If locked and on-body: keep in custody to delay re-lock
- ❌ If off → **Do NOT power on**

---

## 🔗 4. Network Isolation 📡
- 🧤 Use **Faraday bag** or **RF shielded box**
- 🧼 Confirm Airplane Mode + disable radios
- 🔌 Faraday + Power Bank must both be inside the shielding

---

## 🧱 5. Handling Guidelines
- 🧪 Handle with gloves to avoid contamination
- 🧬 Prioritize **traditional forensics** (DNA, prints) before digital
- 🛑 Avoid pressing buttons or screen unless trained

---

## 🗝️ 6. Access Considerations
- 🔐 **Smart Locks** (On-body, Trusted Place/Device) may auto-lock
- 💥 Avoid brute-forcing passcodes (can wipe data!)
- 🔑 Use backups (iTunes/iCloud/MDM) or trusted pairings
- 📵 Disconnect from synced devices (e.g., smartwatch)

---

## 📥 7. Extraction Methods (Acquisition) 🛠️
| Level | Description | Notes |
|-------|-------------|-------|
| 📲 Manual | View & document screen data | Least invasive |
| 📂 Logical | File-level copy | Common & safe |
| 🧱 File System | Includes deleted files | Richer recovery |
| 🧬 Physical (Non-Invasive) | Full memory image | Root access may be needed |
| 🧰 Physical (Invasive) | JTAG, ISP, Chip-Off | Hardware skill required |

🛑 **Note**: Encryption may limit data from physical images.

---

## 💾 8. Storage Media
- 🔌 If ON → Extract w/ SD/SIM inserted
- ❌ If OFF → Remove and acquire separately
- 📇 Capture SIM/UICC card data *before* powering on

---

## ☁️ 9. Other Data Sources
- 🔄 Synced Devices (PC, Tablet, Watch)
- ☁️ Cloud (iCloud, Google Drive, OneDrive)
- 🏢 MDM Systems (Enterprise-level control)

⚠️ **Cloud Forensics**: Jurisdictional limits apply—get legal review.

---

## 📚 10. Post-Acquisition 🧾
- 🧮 Hash acquired data
- 📦 Archive in verified, accessible format
- 📝 Document tools/methods used (per SWGDE/NIST validation)

---

## 🧠 Expert Tips
- 🧪 Validate tools per [NIST CFTT](https://www.nist.gov/itl/ssd/software-quality-group/computer-forensics-tool-testing-program-cftt)
- 📅 Document version-specific behavior (iOS/Android)
- 📷 Always photograph device state **before and after handling**

---

## 📌 References
- 📘 SWGDE Best Practices v1.2 (2020)
- 🏛️ NIST CFTT: https://www.nist.gov/cftt
- ☁️ SWGDE Cloud Acquisition Guide

---

🔚 **Use this guide in the field or lab to ensure best practices in preserving mobile evidence integrity!**
