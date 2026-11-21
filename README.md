# ⚡ FlashDrop P2P — Ultra-Fast Direct File Transfer (100GB+ Ready)

**FlashDrop P2P** is a zero-server, end-to-end encrypted peer-to-peer file and folder transfer web application built on **WebRTC DataChannels**. It enables ultra-fast, direct device-to-device transfers (Mobile ↔ PC or PC ↔ PC) over your local Wi-Fi/LAN or internet without uploading files to any cloud server.

---

## ✨ Key Features

- **🔢 3-Digit Instant Pairing Code & QR Scan:** Connect devices effortlessly using a simple 3-digit numeric code (e.g., `482`) or by scanning the auto-generated QR code.
- **🚀 Turbo 256KB Chunking & 100GB+ Stream:** High-throughput 256KB binary chunking with 4MB backpressure flow control transfers massive files smoothly without browser crashes.
- **💾 Direct-to-Disk Streaming:** Leverages the File System Access API (`showSaveFilePicker`) on desktop Chrome/Edge to write incoming streams directly to your hard drive without using RAM.
- **⛔ Instant Transfer Cancel:** Cancel any ongoing file transfer immediately from either the sender or receiver side.
- **🔐 Two-Sided Mutual Clear Protection:** Transfer history cannot be wiped unilaterally—clearing the list requires explicit approval from the connected peer.
- **📲 Offline-Ready PWA:** Installable as a standalone web app with service worker caching so the interface opens even without internet connectivity.
- **⚡ Auto Screen Wake-Lock:** Prevents mobile and desktop screens from sleeping during large transfers so connections never drop mid-way.

---

## 🛠️ How to Use & Maximize Transfer Speed

1. **Disable Bluetooth:** Turn **OFF** Bluetooth on mobile devices before transferring to prevent 2.4GHz wireless interference.
2. **Use 5GHz Wi-Fi or Mobile Hotspot:** Connect both devices to the same 5GHz router or a 5GHz mobile hotspot for maximum local LAN speeds (30–80+ MB/s). Once paired, mobile data can be turned off while local transfer continues.
3. **Pair Devices:** Open the web app on both devices, scan the QR code, or enter the 3-digit numeric code and click **Connect**.
4. **Install for Offline Access:** Click **Install App** (or use your browser's *Add to Home Screen* option) to launch the app offline anytime.

---

## 📄 Proprietary Notice

All rights reserved. Unauthorized copying, redistribution, or tampering with the application source is prohibited.
