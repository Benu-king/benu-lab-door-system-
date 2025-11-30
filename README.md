# **🔐 BENU LAB DOOR SYSTEM**

### **🔋 Powered by Benayas Wondwosen**

A futuristic hand-gesture–controlled security system designed to open and close a door using **real-time biometric scanning**, **Python gesture detection**, and an **Arduino servo lock mechanism**.
Created and engineered by **Benayas Wondwosen**, combining modern UI design with embedded hardware control.

---

## 📦 **Project Overview**

```
┌───────────────────────────────────────────────────────────────┐
│                      BENU LAB DOOR SYSTEM                     │
│             Futuristic Hand-Scanner Access Control            │
│                   Author: Benayas Wondwosen                   │
└───────────────────────────────────────────────────────────────┘
```

This system detects whether a hand is **open** or **closed**, displays a scanning animation, and sends commands to an Arduino which controls a servo, RGB LED, and buzzer to lock/unlock a door smoothly.

---

## 🧠 **Core Features**

```
┌────────────────────────────────────────────┐
│ ✔ Real-time hand gesture detection         │
│ ✔ Fullscreen futuristic UI (PyQt6)        │
│ ✔ Smooth servo door lock mechanism        │
│ ✔ RGB LED fade effects (red/green)        │
│ ✔ Buzzer feedback for status alerts       │
│ ✔ High-speed serial communication         │
│ ✔ Fully cleaned and optimized code        │
└────────────────────────────────────────────┘
```

---

## 🔧 **System Requirements**

```
┌────────────────────────────────────────┐
│ Python 3.9+                            │
│ Arduino IDE                            │
│ Webcam                                  │
│ USB Cable                              │
│ Servo Motor (SG90/MG90S)               │
│ RGB LED (Common Anode)                 │
│ Buzzer                                 │
└────────────────────────────────────────┘
```

---

## 📁 **Project Files**

```
/benu-lab-door-system
│
├── scanner.py              → Python futuristic interface
├── door_system.ino         → Arduino lock controller
└── README.md               → Project documentation
```

---

## ⚙️ **Installation Guide**

### **1️⃣ Upload Arduino Code**

Load `door_system.ino` into Arduino IDE and upload.

### **2️⃣ Install Python Dependencies**

```bash
pip install opencv-python mediapipe pyqt6 pyglet pyserial
```

### **3️⃣ Run the Program**

```bash
python scanner.py
```

---

## 🔌 **System Workflow**

```
┌─────────────┐     open/close     ┌───────────────┐
│ Hand Scanner │ ────────────────→ │   Arduino      │
└─────────────┘    command "o/c"   │ Servo + LED    │
                                   └───────────────┘
        Futuristic UI shows: Scanning → Granted / Denied
```

---

## 🎨 **UI Highlights**

```
┌─────────────────────────────────────────────┐
│ • Neon glowing interface                    │
│ • Animated scanning line                    │
│ • Hologram-style panels                     │
│ • Smooth transitions                        │
│ • Compact futuristic layout                 │
└─────────────────────────────────────────────┘
```

---

## 🏆 **Created By**

```
┌──────────────────────────────────────────┐
│  👤 Name : Benayas Wondwosen             │
│  🔋 Role : Creator & Lead Developer      │
│  🧠 Skills: Embedded Systems, Python UI  │
│          Gesture Recognition, Robotics   │
└──────────────────────────────────────────┘
```

This entire system is proudly **Powered by Benayas Wondwosen**.

---

## 📄 **License**

Free to use for educational and personal projects.
Please credit **Benayas Wondwosen**.

---
