# 📡 Spatial Scanning using Time-of-Flight (ToF) Sensor

A low-cost spatial scanning system built using a **VL53L0X Time-of-Flight sensor**, **Arduino Uno**, and a **Python-based GUI**. The system performs **1D, 2D, and basic 3D scanning** by combining precise distance measurement with controlled motion using servo and stepper motors.

---

## 🚀 Features
- 📏 Accurate distance measurement using ToF technology  
- 🔄 Multi-axis scanning (servo + stepper integration)  
- 🧠 Real-time data acquisition via Arduino  
- 💻 Python GUI for control and visualization  
- 📊 Live plotting using Matplotlib  
- 📡 Serial communication using PySerial  

---

## 🛠️ Tech Stack

**Hardware:**
- Arduino Uno  
- VL53L0X ToF Sensor  
- Servo Motor (SG90)  
- Stepper Motor (28BYJ-48 + ULN2003)  

**Software:**
- Arduino IDE (C/C++)  
- Python (Tkinter, PySerial, Matplotlib)  

---

## ⚙️ How it Works
1. The ToF sensor emits infrared pulses and measures return time to calculate distance.  
2. Servo and stepper motors sweep the sensor across angles.  
3. Arduino collects distance data and sends it to Python via serial communication.  
4. Python processes and visualizes the scanned data in real time.  

---

## 📊 Output
- 1D distance measurements  
- 2D scanning maps  
- Basic 3D spatial representation  

---

## 🔮 Future Improvements
- Higher resolution ToF sensors (e.g., 8×8 array)  
- Upgrade to ESP32 for wireless communication  
- Improved 3D point cloud visualization  
- Mobile app integration (Flutter)  

---

## 📌 Applications
- Robotics navigation & obstacle detection  
- Autonomous systems  
- AR/VR depth sensing  
- Indoor mapping  

---

## 👥 Contributors
- [Adreet Sarkar](https://github.com/Golden-Adreet)  
- Alok Kumar Pandey  
- Aman Kumar Patel  
- Aman Upadhyay  
- [Anshuman Pandey](https://github.com/anshuman1947)
