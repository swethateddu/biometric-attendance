# 👤 Biometric Attendance System

This project demonstrates a real-time biometric attendance system using fingerprint or facial recognition with Raspberry Pi and Python. It stores attendance data securely in a local database.

---

## 📌 Project Details

- **Duration:** 6 hours  
- **Complexity:** Easy  
- **Portfolio Worthy:** ✅ Yes

---

## 🎯 Learning Outcomes

- Biometric authentication using fingerprint/facial recognition
- Real-time data logging
- Integration with local databases (SQLite)
- Basics of secure access control systems

---

## 📚 Pre-requisites

- Basic Python programming
- Understanding of biometric sensors
- Basic knowledge of databases (SQLite)

---

## 🧰 Required Components

- Raspberry Pi (any model with USB or camera support)
- R305 Fingerprint sensor **OR** USB webcam (for facial recognition)
- Breadboard and jumpers (if using fingerprint sensor)
- Power supply
- Micro SD card (with Raspberry Pi OS)
- SQLite (built-in with Python)

---

## 🛠️ Setup Instructions

### Option A: Fingerprint-based System (R305 sensor)
1. Connect the R305 sensor to Raspberry Pi (TX, RX, VCC, GND)
2. Install libraries:
    ```bash
    pip install pyserial adafruit-circuitpython-fingerprint
    ```
3. Run the code (`fingerprint_attendance.py`)

### Option B: Facial Recognition System
1. Connect USB camera to Raspberry Pi
2. Install libraries:
    ```bash
    pip install opencv-python face-recognition
    ```
3. Run the code (`facial_attendance.py`)

---

## 📈 Real-World Applications

- Automated attendance in schools/colleges
- Secure access for offices or labs
- Employee check-in systems
