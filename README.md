
# 🚗 Smart Car Parking System using Ultrasonic Sensor and Arduino UNO

### 🔧 Mini Hardware Project (TY E&TC)

---

## 📝 Project Description

This is a **smart car parking system** developed using Arduino UNO that manages two parking slots using **ultrasonic sensors**, **IR sensors**, **servo motor**, and an **LCD display**. It includes features like gate automation, real-time parking status, and time-based charging with safety alerts.

---

## 👨‍💻 Team Members

1. **Mayur Jadhav**  
2. **Rushikesh Kale**  
3. **Sachin Chavan**  

**Guide**: Prof. V. V. Gurav Sir  
**Institute**: Brahmdevdada Mane Institute of Technology (BMIT), Solapur  
**University**: Punyashlok Ahilyadevi Holkar Solapur University  
🎉 **Award**: 🥈 _2nd Prize Winner_

---

## 🛠️ Hardware Used

| Component              | Description                                  | Voltage |
|------------------------|----------------------------------------------|---------|
| Arduino UNO            | Main microcontroller                         | 5V      |
| Ultrasonic Sensors (2x)| Measures distance in each parking slot       | 5V      |
| IR Sensors (2x)        | Entry/Exit detection at the gate             | 5V      |
| Servo Motor            | Controls gate opening/closing                | 5V (separate recommended) |
| 16x2 I2C LCD           | Displays real-time slot info and charges     | 5V      |
| LEDs (Red/Green)       | Shows slot status                            | ~2V     |
| Buzzers                | Alerts when car is approaching/parked        | 5V      |
| Breadboard + Wires     | Circuit integration                          | -       |

---

## ⚙️ Features

- Detects vehicle presence using ultrasonic sensors
- Automatic gate control using IR sensors and servo motor
- Real-time LCD display of:
  - Slot status (Empty, Parking, Parked, Approaching)
  - Charges (`C1`, `C2`) increase every 10 sec
- Beep on successful parking
- Smooth multi-angle gate close sequence for safety
- Time-based charges calculated every 10 seconds

---

## 📂 File Structure

- `certificate.pdf` — Participation certificate for Add-On IoT Program
- `README.md` — Project overview file (this)

---

## 🏆 Achievements

✅ Participated in the **Add-on IoT Program (Feb 2025)**  
✅ Secured **2nd Prize** in College Mini Project Competition 🎉

---
