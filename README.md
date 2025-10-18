# soccer_bot_without_microcontroller

## 🧠 Overview
This project is a **dual-motor RC car** powered by two **BTS7960 motor drivers**, a **buck converter**, and **ESC modules** for smooth control.  
It’s designed for stable performance, modular wiring, and compatibility with Arduino or other 5V controllers.

---

## ⚙️ Key Features
- Dual DC motor drive (left & right)
- 5V logic power via buck converter
- PWM-based speed and direction control
- Compact and modular wiring layout
- Supports Arduino, ESP32, or Raspberry Pi

---

## 🔋 Components
- 12V Li-ion / LiPo Battery  
- Buck Converter (LM2596)  
- 2× BTS7960 Motor Drivers  
- 2× ESC Modules  
- 2× 12V DC Gear Motors  
- Common Ground Bus + Power Switch  

---

## ⚡ How It Works
The **battery** powers both motors via BTS7960 drivers,  
while a **buck converter** steps down voltage to 5V for logic control.  
Each driver handles one motor, controlled through **LPWM/RPWM** signals for forward and reverse motion.

---

## 🧩 Control
- **Forward:** Both LPWM = HIGH, RPWM = LOW  
- **Reverse:** Both LPWM = LOW, RPWM = HIGH  
- **Turn Left/Right:** Activate one motor at a time  

---

## 🚀 Future Plans
- Add Bluetooth or Wi-Fi control  
- Implement PID for speed balancing  
- Include obstacle sensors  

---

## 👨‍💻 Author
**Safwan Ul Islam**  
Electronics & Robotics Enthusiast  
North South University  

---

