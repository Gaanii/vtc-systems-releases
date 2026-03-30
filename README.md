# 🚛 VTC SYSTEMS TRACKER

![Version](https://img.shields.io/badge/version-1.0.0-brightgreen?style=for-the-badge)
![Build](https://img.shields.io/badge/build-stable-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows-lightgrey?style=for-the-badge)

---

## 📅 DEV LOG: 31.03.2026 — OFFICIAL v1.0.0 PRODUCTION RELEASE

We are proud to announce the first stable production release. The infrastructure is now fully deployed, featuring a complete refactor of the telemetry engine and a seamless connection to the Driver Hub. This version is built for stability, security, and high-performance tracking.

### ⚡ SYSTEM STATUS: ONLINE

| Component | Status |
|-----------|--------|
| Core Engine | `v1.0.0` — Stable |
| Database | `MongoDB Atlas` — Secure Cloud Sync |
| Auth | `Discord OAuth2` + Subscription Verification |
| Network | Mobile WebSocket Engine Active (Socket.io) |

---

## 🛠️ CHANGELOG (v1.0.0) — WHAT'S NEW

### 🚀 Advanced Job Logging & Critical Fixes
- **Reliable Lifecycle Tracking:** Complete refactor of job detection logic in `main.js`. Fixed previous bugs where logs wouldn't trigger correctly. The system now uses high-precision **Rising Edge** detection to ensure every job is saved.
- **Odometer-Based Distance:** Improved anti-cheat distance calculation using the truck's physical odometer, providing 100% accurate reporting for VTC logistics.

### 🎨 100% Customizable Pro UI
- **Total Visual Control:** Fully personalized dashboard. Upload your own Company Logo and Background Images directly through the settings.
- **Neon Theme Engine:** Select your favorite accent color and adjust background darkness to match your VTC branding.
- **Dynamic Widgets:** Customize your dashboard by toggling elements like the Game Launcher, Stats Grid, Profile Banner, or Recent Deliveries.

### 🎮 Elite In-Game Overlay
- **Next-Gen HUD:** High-performance, transparent overlay with real-time telemetry.
- **Speeding Alerts:** Smart traffic sign detection with visual and acoustic warnings to help you maintain a clean driving record.
- **Technical Gauges:** Live monitoring of air pressure, water temperature, fuel levels, and critical technical warnings (Battery, Oil, Air).

### 📱 Mobile Companion (Dual Screen)
- **Instant QR Sync:** Scan a code from the tracker and turn your smartphone or tablet into a professional second-screen dashboard with zero configuration.
- **Low Latency:** Powered by WebSockets (Socket.io) for real-time truck data streaming to your mobile device.

### 🌐 Global Connectivity
- **Multi-Language Support:** Fully localized in English, Spanish, French, German, and Portuguese.
- **Smart Units:** Automatic conversion between Metric (km/h) and Imperial (mph) based on user preferences.

### 🛡️ Smart Logistics & Automation
- **Game Event Tracker:** Real-time logging of Fines, Collision Damage, and Refueling events synced to your driver profile.
- **Smart Auto-Installer:** Automatically detects your Steam folders and installs the `scs-telemetry.dll` plugin with a single click.
- **Discord RPC:** Rich Presence showing your friends your cargo, destination, and real-time trip progress.

---

## 🔮 ROADMAP

- [ ] **VTC Live Map** — Real-time location tracking for all company members on a shared GPS map.
- [ ] **Economy 2.0** — Detailed maintenance costs and efficiency-based salary systems.
- [ ] **Twitch Integration** — Interactive overlays and event triggers for live streamers.

---

## 📜 HISTORY

<details>
<summary><b>v0.8.0 — Initial Beta Launch (08.02.2026)</b></summary>

> First beta drop. Just kicking off the base infrastructure deployment. The system is live and talking to the Driver Hub.

**System Status at launch:**
- Core: `v0.8.0` (Stable)
- Database: `MongoDB Atlas` (Secure Connection)
- Auth: `Discord OAuth2` + Subscription Check

**What shipped:**
- ✅ **Telemetry Engine:** Initial memory reading implementation (SCS SDK).
- ✅ **Overlay System:** Transparent in-game HUD showing real-time stats.
- ✅ **Cloud Sync:** Auto-syncs jobs right when you finish a delivery.
- ✅ **Security Layer:** Blocks access if you don't have an account on the Web/DB.
- ✅ **Auto-Updater:** OTA updates so you don't have to redownload manually.

</details>

---

<div align="center">

Made with ❤️ by **Gani** · [vtc-systems.com](https://vtc-systems.com)

</div>
