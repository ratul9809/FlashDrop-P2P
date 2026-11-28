# ⚡ FlashDrop P2P — Ultra-Fast Direct File & Folder Sharing

[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Web-10b981?style=for-the-badge)]()
[![Technology](https://img.shields.io/badge/Tech-WebRTC%20%7C%20PeerJS%20%7C%20PWA-0f172a?style=for-the-badge)]()
[![Release](https://img.shields.io/badge/Download-Android%20APK-2563eb?style=for-the-badge)](../../releases/latest)

**FlashDrop P2P** is a lightweight, high-speed peer-to-peer (WebRTC) file and folder sharing application built for instant transfers between Android, Windows, Mac, and Linux without cloud uploads or file size limits.

---

### 📲 Download & Live Access
- **Android App (APK):** [Download Latest Release](../../releases/latest)
- **Live Web App:** [https://live-stream.us.to/transfer/](https://live-stream.us.to/transfer/)

---

### 🔥 Core Highlights
1. **3-Digit Pairing & Instant QR:** No sign-up or login required—pair any two devices with a 3-digit code or QR code.
2. **Direct-to-Disk Streaming:** Supports massive files (100GB+) with live speed (MB/s), ETA, and instant cancel controls.
3. **Offline Hotspot Mode:** Once paired, turn off mobile internet and transfer files over local Wi-Fi/Hotspot at maximum speed.
4. **In-App Auto-Update & Remote Control:** Dynamic server-side version check (`ads-config.json`) with optional or forced update prompts and remote ad control.
5. **Encrypted Text & Link Chat:** Quickly share URLs, passwords, or notes with one-tap copy and mutual two-sided permission for clearing transfer history.

---

### 📂 Repository Structure
- `index.html` — Core single-file responsive UI, WebRTC engine, In-App Update modal, and remote configuration loader.
- `manifest.json` — Progressive Web App (PWA) manifest for standalone installation.
- `sw.js` — Service Worker (`v6`) for offline caching and instant load performance.
- `ads-config.json` — Remote configuration file for dynamic ad management and in-app version updates.
