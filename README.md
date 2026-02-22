# IoT CTF Challenge Pack

Welcome to the **IoT CTF Challenge Pack**! 🕹️  

This repository contains beginner-friendly IoT security challenges designed to simulate real-world IoT devices and firmware. Each challenge includes files you can analyze locally — no server required.

---

## 🏆 Challenges

### 1️⃣ MQTT Challenge
- **Scenario:** A smart IoT device communicates over MQTT. The broker might be publicly accessible.
- **Files:** `MQTT/mqtt_message.pcapng`
- **Tools you may use:** Wireshark, `mosquitto_sub`
- **Objective:** Analyze the capture file and retrieve the hidden flag.
- **Flag format:** `flag{...}`
- **Difficulty:** Easy

---

### 2️⃣ Linux Firmware Challenge
- **Scenario:** You received a firmware image from a smart IoT device. It contains a Linux root filesystem.
- **Files:** `Firmware_flag/firmware.bin`, `Firmware_flag/challenge.txt`
- **Tools you may use:** `tar`, `binwalk`, `strings`, `hexdump`, `cat`
- **Objective:** Extract the firmware and locate the hidden flag.
- **Flag format:** `flag{...}`
- **Difficulty:** Medium

---

## 🛠 Recommended Tools

- Wireshark (`sudo apt install wireshark`)
- Mosquitto clients (`mosquitto_sub`, `mosquitto_pub`)
- binwalk (`sudo apt install binwalk`)
- strings, hexdump, cat (usually pre-installed on Linux)

---

## 📦 How to Play

1. Clone the repository:

```bash
git clone https://github.com/<yourusername>/IoT_CTF.git
cd IoT_CTF