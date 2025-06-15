# 🛡️ OCTO CyberSim - Telegram-Controlled Cyber Attack Simulator

> **⚠️ Disclaimer:** This project is for **educational and authorized testing** only. It must not be used for unauthorized activities. Misuse can result in legal consequences. The author assumes no liability for improper use.

---

## 📌 Overview

**OCTO CyberSim** is a **Telegram-based network simulation tool** designed to demonstrate how various network-layer and application-layer denial techniques function in real-time. It allows authorized red teamers, researchers, and cybersecurity enthusiasts to understand how different forms of traffic manipulation can affect system behavior — all controlled via a Telegram bot.

---

## 🎮 Features

- 🎛️ **Interactive Bot Interface** — Controlled entirely via Telegram inline menus.
- 🌐 **Supports Multiple Attack Simulations:**
  - `SYN Flood` (TCP exhaustion)
  - `UDP Amplification` (simulated bandwidth surge)
  - `Slowloris` (HTTP starvation)
  - `ICMP Ping Flood` (layer 3 simulation)
  - `NXDOMAIN Attack` (DNS overload)
  - `WebSocket Flood` (layer 7 abuse)
- ⚙️ **Multi-threaded Execution** for realism.
- 🧠 Built-in IP resolution and spoofed interaction modes.

---

## 🧠 Attack Methods (Simulated)

| ID | Technique Name                 | Description                          |
|----|-------------------------------|--------------------------------------|
| 1  | SYN Flood                     | Simulated TCP handshake exhaustion  |
| 2  | UDP Amplification             | Simulated UDP flood via DNS servers |
| 3  | HTTP Slowloris                | Simulated slow HTTP header trickle  |
| 4  | ICMP Ping Storm               | Simulated ICMP echo flood           |
| 5  | DNS Water Torture             | Simulated NXDOMAIN DNS spam         |
| 6  | WebSocket Armageddon         | Simulated WebSocket abuse           |

---

## 🤖 Telegram Integration

This tool requires a [Telegram Bot Token](https://core.telegram.org/bots#3-how-do-i-create-a-bot) and your **Admin Chat ID** to operate.

### Setup:

```bash
pip install -r requirements.txt
python octo_cybersim.py
