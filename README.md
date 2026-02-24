# TempFluxLink ⚡

**The official PC telemetry server for the TempFlux mobile app.**

TempFluxLink is a lightweight, high-performance Windows background service that securely broadcasts your system's hardware metrics over your local network directly to your mobile device. 

Built for enthusiasts pushing their systems to the limit, it effortlessly handles monitoring high-end, heavily tuned rigs. Whether you are tracking the water-coolant performance on an undervolted RTX 3080 Ti or keeping an eye on the thermals of an overclocked Ryzen 9 5900X during intense gaming sessions, TempFluxLink delivers zero-latency data straight to your screen.

---

## 🚀 Quick Start Guide

Getting your PC connected to the TempFlux mobile app takes less than a minute.

### 1. Download the Server
Navigate to the [Releases](#) tab on the right side of this GitHub page and download the latest `TempFluxLink.zip` file.

### 2. Extract and Run
Extract the `.zip` folder anywhere on your PC. Double-click `TempFluxLink.exe` to start the local server. 
*Note: TempFluxLink runs completely locally and never sends your hardware data to the cloud.*

### 3. Connect Your Mobile App
When the console window opens, it will display your computer's local **IP Address** and **Port**. 
1. Open the TempFlux app on your phone.
2. Navigate to the **Settings** tab.
3. Enter the IP address and Port displayed in the PC console.
4. Tap **Save Configuration**.

You are now officially connected! Switch over to the Dashboard tab to view your real-time hardware telemetry.

---

## 🛡️ Troubleshooting & Firewalls

If your mobile app says "Connection Failed," your Windows Firewall is likely blocking the local broadcast.

**To fix this:**
1. Press the Windows Key and type **Windows Defender Firewall**.
2. Click **Allow an app or feature through Windows Defender Firewall** on the left menu.
3. Click **Change settings** (requires admin rights).
4. Click **Allow another app...** at the bottom, browse to your extracted `TempFluxLink.exe`, and add it.
5. Ensure both the **Private** and **Public** checkboxes are ticked for TempFluxLink.
6. Click OK and restart the TempFluxLink server.

---

## 🛠️ System Requirements
* Windows 10 or Windows 11
* .NET 8.0 Desktop Runtime (Prompted automatically if missing)
* Both the PC and Mobile device must be connected to the same local network (Wi-Fi or Ethernet).
