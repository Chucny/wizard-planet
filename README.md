# 🪄 Wizard Planet
### An open-source AR geolocation adventure built for the modern web.

[**Play the Game ➔**](https://chucny.github.io/wizard-planet)

---

## 🌍 Project Overview
**Wizard Planet** is a mobile-first web application that turns your physical environment into a multiplayer arena. By combining real-time GPS tracking with Augmented Reality, it creates a unique scavenger hunt experience directly in your browser.

---

## ⚙️ Core Mechanics

### 📍 Proximity Spawning
The game engine detects movement with **2.5m precision**. As you walk, the logic dynamically generates new encounters based on your real-time coordinates.

### 📷 Hybrid AR
Features a dual-mode catch system. You can switch between a stylized 3D background or a **live AR camera feed** with automatic back-camera prioritization.

### 🤝 Defeat Polygon in Raids!
Global boss battles are synchronized via **MQTT**. Join friends instantly using session-specific raid codes for real-time collaborative damage.

---

## 🛠️ Technical Stack
Built using a "no-framework" approach for maximum performance and low latency:

* **Vanilla JS (ES6+):** Core game logic and rendering.
* **Firebase:** Realtime Database for cloud-synced player inventories.
* **MQTT / WebSockets:** HiveMQ broker for global raid synchronization.
* **Geolocation API:** High-accuracy GPS tracking logic.
* **OpenStreetMap:** Dynamic map tile rendering.

---

## 🚀 Getting Started
1. Open [https://chucny.github.io/wizard-planet](https://chucny.github.io/wizard-planet) on your mobile browser.
2. **Enable Location Services** when prompted.
3. For AR Mode, allow **Camera Access**.
4. *Note: A secure (HTTPS) connection is required for GPS and Camera features.*

---

> **Developer Note:** This project was designed to explore the limits of the mobile web browser as a gaming platform.<br><strong>Copyright &copy; Chucny 2026</strong>

---
© 2026 Wizard Planet • Built with focus on privacy and performance.
