from pathlib import Path

# Markdown content for the NeoPack README
readme_content = """
<!-- Header Typing Animation -->
<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&duration=3500&pause=1000&color=00F7FF&center=true&vCenter=true&multiline=true&width=800&height=120&lines=🎒+NeoPack+-+IoT+Smart+Backpack;Smarter+Packing.+Safer+Days.+Connected+Life." alt="Typing SVG" />
</h1>

<!-- Video Preview -->
<p align="center">
  <a href="https://youtu.be/QEiaLV7WJts" target="_blank">
    <img src="https://img.youtube.com/vi/QEiaLV7WJts/maxresdefault.jpg" alt="NeoPack Demo Video" width="80%" style="border-radius: 20px; box-shadow: 0 4px 20px rgba(0,0,0,0.4);" />
  </a>
  <br/>
  📺 <b><i>Click to Watch the Demo</i></b>
</p>

---

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Platform-IoT-blue?style=for-the-badge&logo=raspberrypi" />
  <img src="https://img.shields.io/badge/App-ReactNative-purple?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/Cloud-Supabase-brightgreen?style=for-the-badge&logo=supabase" />
  <img src="https://img.shields.io/badge/MCU-ESP32-black?style=for-the-badge&logo=espressif" />
</p>

---

<!-- Abstract -->
<h2 align="center">
  🧠 <span style="background: linear-gradient(to right, #00c6ff, #0072ff); -webkit-background-clip: text; color: transparent;">Abstract</span>
</h2>

> **NeoPack** is not just smart. It's **context-aware**, **mission-ready**, and **personalized for your daily grind**.  
> From missed books to rainstorms or overloaded bags—NeoPack’s got your back (literally).

---

## 🌟 The Problem vs. Our Solution

<table align="center">
<tr>
<td width="45%">

### 🧱 Traditional Backpacks

- ❌ No item detection  
- ❌ Unaware of weather  
- ❌ Can’t detect weight  
- ❌ Zero mobile sync  
- ❌ No device monitoring  

</td>
<td width="10%" align="center">➡</td>
<td width="45%">

### 🚀 NeoPack Advantages

- 📘 Detects forgotten books via ESP32-C3  
- 🌧 Warns you before it rains  
- ⚡ Monitors device charge levels  
- 🏋 Alerts if overloaded  
- 📱 Full mobile control via NeoPulse app  

</td>
</tr>
</table>

---

## 🔑 Key Features

| 🔍 Feature | 💬 Description |
|-----------|----------------|
| **📖 Smart Book Tracking** | Detects missing books using EMI-triggered ESP32-C3 modules |
| **🌧 Weather Awareness** | Real-time weather forecast and umbrella alerts via API |
| **🔋 Battery Monitoring** | Tracks charge levels of devices inside your bag |
| **⚖ Load Detection** | Weight sensors flag ergonomically unsafe loads |
| **📲 NeoPulse App** | Real-time control hub for books, weather, battery, and alerts |

---

## 🛠️ Hardware Stack

| Component | Purpose |
|----------|---------|
| **ESP32-S3** | Central controller in backpack |
| **ESP32-C3 (xN)** | Book-attached modules triggered by EMI |
| **EMI Rail System** | Power delivery and activation |
| **HX711 + Load Cell** | Weight sensing module |
| **Battery Monitor** | Tracks charge of laptop/power banks |
| **LEDs & Vibration Motor** | Alert system for quick feedback |

---

## 💻 Software Stack

```yaml
App:        React Native (NeoPulse)
Backend:    Supabase (Realtime DB + Auth)
Cloud API:  Weather Forecast (OpenWeather or similar)
Firmware:   ESP-IDF (C/C++) for ESP32 modules
Security:   SHA256 hashing + Token-based Auth
