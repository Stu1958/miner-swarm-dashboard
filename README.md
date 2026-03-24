# ⛏️ Miner Swarm Dashboard (ESP32 CYD)

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Hardware: ESP32-CYD](https://img.shields.io/badge/Hardware-ESP32--CYD-blue)

**The ultimate desk-side companion for your mining fleet.** Monitor up to 8 miners (Avalon, Bitaxe, N-Series) in real-time on your 2.8" Cheap Yellow Display.

---

## 🚀 Quick Start
Don't want to mess with code? Use the **official Web Flasher**:
### 👉 [Launch Web Installer](https://stu1958.github.io/miner-swarm-dashboard/)

---

## 🛠️ Configuration & Naming
To ensure the dashboard auto-detects your hardware, keep names under **8 characters** and follow these rules (Capitals are OK):

| Miner Model | Keyword Required | Example Name |
| :--- | :--- | :--- |
| **Avalon Nano 3S** | `NANO` + `3S` | `N3S_RIG` |
| **Avalon Nano 3** | `NANO` + `3` | `N3_MAIN` |
| **N-Series (NX6/NQ6)** | Starts with `NX` or `NQ` | `NX6_01` |
| **Standard Bitaxe** | Any other name | `GAMMA_1` |

## ✨ Features
- **Persistent Stats:** Saves "Best Difficulty" to NVS (specifically for Avalon Nano).
- **Auto-Hardware Detection:** Custom logic based on miner hostname.
- **Color-Coded Temps:** Visual warnings for overheating units.
- **Universal Driver:** Supports both ILI9341 and ST7789 display panels.

## ❤️ Support the Developer
If this project helps you manage your swarm, consider buying me a coffee!
- [PayPal](https://www.paypal.com/paypalme/stub1958)
- [Buy Me a Coffee](https://buymeacoffee.com/stuartbinnz)
