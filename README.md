# IV-Internet-of-Things

# 🎒 NeoPack - IoT-Based Smart Backpack

## 🧠 Abstract

**NeoPack** is a context-aware IoT Smart Backpack designed to enhance everyday efficiency and security. Whether it's forgetting a book, walking into a rainstorm, or carrying an overloaded bag, NeoPack proactively alerts you before problems arise. The system integrates ESP32 microcontrollers, sensors, and mobile connectivity to provide real-time, intelligent feedback—making your backpack smarter than ever.

---

## 💡 The Idea

In an era of smart everything, the backpack remains dumb. NeoPack changes that.

This intelligent backpack uses **ESP32-C3 modules mounted in books**, activated via **an EMI-triggered rail system**. These modules broadcast signals verified by an ESP32-S3 in the bag. Combine that with weather forecasting, battery level monitoring, and weight detection—and you have a personal assistant strapped to your shoulders.

**NeoPack = Smart Alerts + Organized Packing + Real-Time Monitoring**

---

## 🎯 Objective

To engineer a smart backpack that:
- Uses **EMI-triggered ESP32-C3 modules** to detect missing books
- Monitors battery levels of electronic devices
- Detects bag overweight conditions
- Provides real-time alerts via a custom mobile app
- Retrieves contextual weather updates

---

## 🔍 Problems with Traditional Backpacks

- ❌ No way to verify packed books or items  
- ❌ Unaware of weather—no reminders to carry umbrella  
- ❌ No alerts for low battery levels of devices  
- ❌ Users carry overweight bags without feedback  
- ❌ No interaction or alerts via mobile  

---

## ✅ Our Solution – NeoPack

NeoPack turns the backpack into a smart ecosystem:
- 📚 Uses **EMI-triggered ESP32-C3 modules** embedded in books  
- 📡 Gets live weather updates and recommends carrying an umbrella  
- 🔋 Tracks charge level of connected devices and alerts user  
- ⚖️ Detects bag overweight with a load sensor and gives real-time warnings  
- 📱 Integrates with a **mobile app** to deliver alerts and dashboard info  

---

## 🔑 Key Features

### 1. 📚 Smart Book Tracking (No NFC!)  
Each book has an **ESP32-C3** activated via a custom **EMI-trigger rail**. The backpack’s **ESP32-S3** listens for Bluetooth signals and alerts you if any expected book is missing before you leave.

### 2. 🌧️ Weather-Based Alerts  
Real-time weather forecasts retrieved via API notify users to carry an umbrella if rain is expected.

### 3. 🔋 Battery Monitoring  
Tracks charge status of laptops or power banks inside the backpack and sends alerts to the app when battery is low.

### 4. ⚖️ Load Detection  
Uses a load sensor to calculate the weight of the backpack and alerts the user if it exceeds ergonomic safety limits.

### 5. 📲 NeoPulse Mobile App  
Provides real-time alerts, interactive dashboards, and status indicators for books, weather, battery, and weight—all synced with the smart bag.

---

## 🛠 Hardware Components

- ESP32-S3 microcontroller (Main controller inside bag)  
- ESP32-C3 modules (One per book)  
- EMI power rail (Triggers ESP32-C3 via electromagnetic induction)  
- Load sensor (Weight detection)  
- Battery level monitor  
- Haptic motors and LED indicators for feedback  

---

## 💻 Software Components

- **NeoPulse Mobile App** (Dark/Light Mode, Real-time sync)  
- **Supabase** for cloud sync & offline support  
- **REST APIs** for communication between backpack and app  
- **Weather API** integration for forecast alerts  
- **Secure Communication** using SHA256 authentication  

---

## 📱 NeoPulse App Screens

- **Home**: Overview of all systems and alerts  
- **Books**: Real-time status of packed books  
- **Weather**: Forecast alerts and umbrella reminders  
- **Battery**: Monitoring of device charge levels  
- **Settings**: Customization and theme toggles  

---

## Our Project Demo

- Here's the youtube link for our project demo:
- [🔥 This Backpack Knows What You Forgot! 😱 | Meet NeoPack – The Smartest IoT Bag Ever](https://youtu.be/QEiaLV7WJts)


## 👥 Authors

- **Manoharan K** – 230701177  
- **Monic Auditya A** – 230701194  
- **Monish D Y** – 230701195  

---

## 📌 License

This project is for academic demonstration. Licensing will be defined for production versions.

---

> "Not just smart. Context-aware. Mission-ready. That’s **NeoPack**."
