# FuturonESP8266

**FuturonESP8266** is an easy-to-use Arduino library for ESP8266 that uploads sensor data to **Futuron Cloud** using simple formatted messages like:


The library:
- Parses **multiple sensor-value pairs**
- Uploads to cloud **instantly** using HTTPS
- Builds URLs using your **username**
- Uses Bearer Token authentication
- Works with **SoftwareSerial** or **HardwareSerial**
- Supports **real-time continuous streaming**

---

## ✨ Features

- ✔ Unlimited sensor support (`s1`, `s2`, `s3`, `s100`, etc.)
- ✔ Order does **NOT** matter
- ✔ Automatic URL creation
- ✔ HTTPS POST with Bearer token
- ✔ No SSL certificate needed (`setInsecure()`)
- ✔ Designed for IoT + gateway devices
- ✔ Lightweight and fast
- ✔ Perfect for external MCU → ESP8266 → Cloud

---

## 📁 Library Folder Structure

FuturonESP8266/
├── src/
│ ├── FuturonESP8266.h
│ └── FuturonESP8266.cpp
├── examples/
│ └── BasicUsage/
│ └── BasicUsage.ino
└── library.properties
---

## 🚀 Installation

### 1. Manual Installation (ZIP Method)

Follow these steps to install the library manually:

#### **Step 1 — Download the Library**
- Click the **Code → Download ZIP** button on this repository  
- Save the ZIP file to your computer  

#### **Step 2 — Install via Arduino IDE**
1. Open **Arduino IDE**
2. Go to:  
   **Sketch → Include Library → Add .ZIP Library...**
3. Select the downloaded ZIP file
4. Arduino IDE will add it automatically

You will now see **FuturonESP8266** inside:  
**Sketch → Include Library**  
and  
**File → Examples → FuturonESP8266**

---




