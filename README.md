# 🔐 IoT-Based Smart Lock System Using ESP32 & Mobile Biometric Authentication

An advanced IoT-based smart lock system that combines embedded systems, mobile application development, and secure communication to provide a reliable and low-cost access control solution.

---

## 📌 Overview
This project presents the design and implementation of a smart lock system based on the ESP32 microcontroller. The system enhances traditional locking mechanisms by integrating digital authentication methods, including PIN-based access and biometric authentication through a mobile application.

The system supports both local and remote control using MQTT communication, enabling real-time monitoring and secure access from anywhere.

---

## 🚀 Key Features
- 🔑 Keypad-based PIN authentication  
- 📱 Mobile application (Unity) for remote control  
- 👆 Biometric authentication (Fingerprint via smartphone)  
- 🌐 MQTT-based communication  
- 🔒 Multi-layer security system  
- 🚫 Brute-force protection (failed attempts limit)  
- 📟 Real-time status display using LCD  
- 🔔 Buzzer alerts for unauthorized access  
- ⏳ Temporary guest access codes  
- ⚡ Low power consumption with efficient design  

---

## 🧠 System Architecture
The system is centered around the ESP32 microcontroller, which acts as the main controller.

### 🔄 Workflow:
1. User enters PIN via keypad OR uses mobile app  
2. Mobile app verifies biometric authentication (fingerprint)  
3. Command is sent via MQTT  
4. ESP32 processes authentication  
5. Relay is activated → Solenoid unlocks door  
6. LCD + Buzzer provide feedback  

---

## 🔌 Hardware Components
- ESP32 Microcontroller  
- 12V Solenoid Lock  
- Relay Module (5V)  
- 2N2222 Transistor  
- 1N4007 Flyback Diode  
- LM7805 Voltage Regulator  
- Capacitors (100nF, 1000µF)  
- 4×4 Keypad  
- 16×2 LCD Display (I2C)  
- Active Buzzer  

---

## 💻 Software & Technologies
- Embedded C (Arduino IDE)  
- MQTT Protocol (IoT Communication)  
- Wi-Fi Networking  
- Unity (Mobile Application Development)  
- Biometric Authentication (Fingerprint API)  

---

## 🔐 Security Features
- PIN authentication system  
- Biometric verification via mobile  
- Failed attempt limitation (lockout mechanism)  
- Unauthorized IP blocking  
- Secure MQTT communication  
- Real-time monitoring and alerts  

---

## 📊 Performance
- ⏱️ Response Time: < 1 second  
- 🎯 Authentication Accuracy: ~99%  
- ⚡ Power Consumption: ~6.36W during activation  
- 🔋 Low power consumption in idle mode  

---

## 💰 Cost Analysis
- Total Cost: ≈ 27 USD  
- Significantly cheaper than commercial smart locks (120–250 USD)  

---

## 📱 Mobile Application (Unity)
The mobile application was developed using Unity and provides:
- Remote lock/unlock functionality  
- Biometric authentication (fingerprint)  
- Secure communication with ESP32  
- User-friendly interface  

---

## 🔄 Communication Protocols
- MQTT (Primary communication)  
- HTTP (Supporting communication for mobile app)  

---

## 🧪 Testing & Validation
- Hardware tested using Proteus simulation  
- Real-time system validation performed  
- Reliable operation under different conditions  
- Stable voltage and current performance  

---

## 🚀 Future Improvements
- 🔐 End-to-end encryption (TLS/SSL)  
- ☁️ Cloud-based monitoring system  
- 📊 Data logging and analytics  
- 👁️ Face recognition integration  
- 📱 Enhanced mobile UI/UX  

---

## 👨‍💻 Authors
- Yahia Alafifi  
- Amir Abu Samra  

---

## 🎓 Academic Information
Smart Systems Engineering  
Islamic University of Gaza  
Graduation Project – 2026  

---

## 📌 Project Goal
To develop a secure, scalable, and affordable IoT-based smart lock system that integrates embedded systems with modern mobile technologies for enhanced access control.

---

## ⭐ Notes
This project demonstrates strong integration between:
- Embedded Systems  
- IoT Communication  
- Mobile Application Development  
- Security Engineering  

---

## 📷 Demo (Optional)
<img width="325" height="666" alt="لقطة شاشة 2026-03-02 134332" src="https://github.com/user-attachments/assets/c9f4e4d5-7fd1-42ba-ade4-8acba75769d7" />
<img width="331" height="665" alt="لقطة شاشة 2026-03-02 134406" src="https://github.com/user-attachments/assets/4b92f08f-746f-40bd-bcaf-561c48f6448b" />
<img width="332" height="665" alt="لقطة شاشة 2026-03-02 134424" src="https://github.com/user-attachments/assets/405270d7-8253-4e47-83dc-47beea9c50b5" />
<img width="329" height="669" alt="لقطة شاشة 2026-03-02 134415" src="https://github.com/user-attachments/assets/9a659f94-e9d2-475d-8629-d6bddb0de19f" />

