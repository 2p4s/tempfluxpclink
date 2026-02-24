# TempFluxLink ⚡

**The official PC telemetry server for the TempFlux mobile app.**

TempFluxLink is a lightweight, high-performance Windows background service that securely broadcasts your system's hardware metrics over your local network directly to your mobile device. 

Built for enthusiasts pushing their systems to the limit, it effortlessly handles monitoring high-end, heavily tuned rigs. Whether you are tracking the water-coolant performance on an undervolted RTX 3080 Ti or keeping an eye on the thermals of an overclocked Ryzen 9 5900X, TempFluxLink delivers zero-latency data straight to your screen.

---

## 🚀 Quick Start Guide

Getting your PC connected to the TempFlux mobile app takes less than a minute.

### 1. Download the Installer
Navigate to the [Releases](https://github.com/2p4s/tempfluxpclink/releases) tab and download the latest `TempFluxLink_Installer.exe`.

### 2. Run the Setup
Run the installer. It will automatically:
* Install the TempFluxLink service.
* Register it to start automatically with Windows.
* Configure your Windows Firewall to allow the local telemetry broadcast.

### 3. Connect Your Mobile App
Once installed, the service runs silently in the background. 
1. Open the **TempFlux** app on your phone.
2. Navigate to the **Settings** tab.
3. Enter your PC's local **IP Address** (you can find this by typing `ipconfig` in CMD or looking at your network settings).
4. Tap **Save Configuration**.

You are now officially connected! Switch over to the Dashboard tab to view your real-time hardware telemetry.

---

## 🛠️ System Requirements
* **OS:** Windows 10 or Windows 11 (x64)
* **Hardware:** Compatible with all modern CPU/GPU sensors (Optimized for NVIDIA/AMD setups).
* **Network:** Both the PC and Mobile device must be connected to the same local network (Wi-Fi or Ethernet).
* **Dependencies:** None. The installer is self-contained and includes all necessary runtimes.

---

## 🛡️ Privacy & Security
TempFluxLink is built with privacy as a priority.
* **Local Only:** Your hardware data never leaves your local network. No cloud accounts, no external servers.
* **Lightweight:** Designed to run with near-zero CPU impact, ensuring your gaming performance remains unaffected.
* **Transparent:** Only broadcasts sensor data required for the TempFlux Dashboard.
