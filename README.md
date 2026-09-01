<div align="center">

<img src="https://github.com/shubhambelbase/tacnet/releases/download/v2.5.4/tacnet_logo.png" alt="TAC-NET Logo" width="220" />

# TAC-NET

### **Decentralized Military-Grade Tactical Push-to-Talk (PTT) Transceiver**

[![Release](https://img.shields.io/github/v/release/shubhambelbase/tacnet?style=for-the-badge&color=00E676&label=LATEST%20BETA)](https://github.com/shubhambelbase/tacnet/releases/latest)
[![Platform](https://img.shields.io/badge/PLATFORM-ANDROID%208.0%2B-00E676?style=for-the-badge&logo=android&logoColor=white)](https://github.com/shubhambelbase/tacnet/releases/latest)
[![Security](https://img.shields.io/badge/SECURITY-AES--256--GCM-00E676?style=for-the-badge&logo=lock&logoColor=white)](https://github.com/shubhambelbase/tacnet)
[![Network](https://img.shields.io/badge/NETWORK-OFF--GRID%20MESH-00E676?style=for-the-badge)](https://github.com/shubhambelbase/tacnet)
[![Build](https://img.shields.io/badge/BUILD-v2.5.4--BETA-orange?style=for-the-badge)](https://github.com/shubhambelbase/tacnet)

<br />

[📥 **DOWNLOAD BETA APK (v2.5.4)**](https://github.com/shubhambelbase/tacnet/releases/latest/download/app-debug.apk) • [⚡ **RELEASE NOTES**](https://github.com/shubhambelbase/tacnet/releases) • [📡 **CHANNEL SPECIFICATIONS**](#-channel-presets)

</div>

---

## ⚡ Overview

**TAC-NET** is an advanced, decentralized tactical Push-to-Talk (PTT) walkie-talkie communication system designed for high-performance off-grid operations. It enables real-time encrypted voice streaming, tactical text messaging, autonomous peer mesh discovery, and emergency distress beacons over local Wi-Fi and mobile hotspot networks — **100% serverless, zero-cloud, and fully functional without internet access**.

---

## 🛡️ Key Features

### 🎙️ Real-Time Voice Transceiver & LCD Dashboard
- **Backlit Military LCD Ticker**: Live animated dot-matrix tactical message feed embedded directly into the central LCD dashboard with seamless auto-marquee for long messages and blinking cursor.
- **SOS Auto-Dismissal**: Pressing the Push-to-Talk (PTT) key immediately acknowledges and dismisses active emergency distress alerts from the LCD ticker.
- **Push-to-Talk (PTT)**: Instant, zero-lag voice transmission with clean half-duplex muting and haptic confirmation.
- **4:1 IMA-ADPCM Voice Codec**: Compresses 16kHz PCM down to lightweight 244-byte UDP packets, preventing packet loss and buffer congestion over Wi-Fi and hotspot connections.
- **Hardware DSP Integration**: Built-in Acoustic Echo Cancellation (AEC), Noise Suppression (NS), Automatic Gain Control (AGC), and configurable Squelch Gate.
- **Procedural Radio FX**: Authentic NASA/Mil-Spec Roger Beeps, Key-Up Chirps, and Squelch Tails.

### 📱 Tactical Comms & Keyboard UX
- **Keyboard-Aligned Chat**: Full IME inset handling ensures text inputs and send buttons sit pinned cleanly above the soft keyboard without screen occlusion.
- **TopBar Tactical Menu**: Quick dropdown access to **Tactical Settings** and the detailed **About Tac-Net** intelligence dossier.
- **Comprehensive About Screen**: Explains system architecture, dual-path multicast/broadcast transceiver, hardware requirements, RF range limitations, and build specifications.

### 🔐 Military-Grade Security
- **End-to-End Encryption (E2EE)**: Hardware-accelerated **AES-256-GCM** authenticated cipher.
- **PBKDF2 Key Derivation**: Derives 256-bit cryptographic keys from custom tactical passphrases.
- **Replay & Tamper Protection**: Unique 64-bit sender tokens and monotonic sequence indexing.

### 📡 Autonomous Tactical Mesh Discovery
- **Peer Radar & Presence**: Discovers surrounding operators with live battery percentage, callsigns, channel status, and GPS proximity.
- **Dual-Path Routing**: Simultaneous UDP Multicast and directed Subnet Broadcast dispatch with LRU jitter de-duplication.

### 🎛️ Tactical Utility Suite
- **"Say Again" Instant Replay**: Rolling 30-second transmission cache to replay missed voice traffic with one tap.
- **Tactical Text Messaging & Distress SOS**: Encrypted silent messaging and emergency priority distress sirens.
- **Floating HUD Overlay**: Compact tactical overlay window allowing full PTT operation over maps and navigation apps.
- **Hardware Key Trigger**: Configurable physical button PTT (Volume Up, Volume Down, Headset Hook, Camera Key).
- **In-App OTA Updater**: 1-tap seamless updates via GitHub Release delivery.

---

## 📻 Channel Presets

| Channel | Frequency (MHz) | Multicast Group | UDP Port |
|:-------:|:---------------:|:---------------:|:--------:|
| **CH-01** | `462.5625 MHz` | `239.255.50.1` | `5051` |
| **CH-02** | `462.5875 MHz` | `239.255.50.2` | `5052` |
| **CH-03** | `462.6125 MHz` | `239.255.50.3` | `5053` |
| **CH-04** | `462.6375 MHz` | `239.255.50.4` | `5054` |
| **CH-05** | `462.6625 MHz` | `239.255.50.5` | `5055` |
| **CH-06** | `462.6875 MHz` | `239.255.50.6` | `5056` |
| **CH-07** | `462.7125 MHz` | `239.255.50.7` | `5057` |
| **CH-08** | `467.5625 MHz` | `239.255.50.8` | `5058` |
| **CH-09** | `467.5875 MHz` | `239.255.50.9` | `5059` |
| **CH-10** | `467.6125 MHz` | `239.255.50.10` | `5060` |
| **CH-11** | `467.6375 MHz` | `239.255.50.11` | `5061` |
| **CH-12** | `467.6625 MHz` | `239.255.50.12` | `5062` |
| **CH-13** | `467.6875 MHz` | `239.255.50.13` | `5063` |
| **CH-14** | `467.7125 MHz` | `239.255.50.14` | `5064` |

---

## 📲 Quick Installation

1. Navigate to the **[Latest Beta Release](https://github.com/shubhambelbase/tacnet/releases/latest)**.
2. Download **`app-debug.apk`**.
3. Open the downloaded APK on your Android device to install.
4. Ensure all devices are connected to the same Wi-Fi network or a portable Mobile Hotspot.
5. Select a matching channel on all devices and hold **PTT** to transmit!

---

## 🔒 Privacy & Off-Grid Guarantee

- **Zero Cloud**: No external servers, logins, accounts, or telemetry.
- **Zero Internet Required**: Works completely in airplane mode over local Wi-Fi / Hotspots.
- **Ephemeral Storage**: Voice transmissions stream directly to speakers in real-time with zero cloud logging.

---

<div align="center">
<sub>TAC-NET Tactical Systems • Built & Engineered by Shubham • Mission-Critical Off-Grid Communications</sub>
</div>
