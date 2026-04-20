# 🏠 IoT Based Smart Home with Secure Authentication

## 📌 Project Overview
This project demonstrates a **secure IoT-based Smart Home system** where multiple devices such as lights, fans, doors, and windows can be monitored and controlled remotely.  

Unlike traditional smart home systems that rely on a shared WiFi password, this project implements **WPA2-Enterprise security with a RADIUS server**, ensuring that each device is authenticated individually.

---

## 🎯 Objectives
- Design a smart home system using IoT devices
- Implement **secure wireless communication**
- Replace shared password authentication with **individual credentials**
- Integrate **RADIUS (AAA)** for centralized authentication
- Enable remote monitoring and control via web interface

---

## 🛠️ Technologies Used
- Cisco Packet Tracer
- IoT (Internet of Things)
- WPA2 Enterprise Security
- RADIUS Server (AAA)
- Networking Concepts (DHCP, IP Addressing, Wireless Networks)

---

## 🧱 System Architecture
The system follows a **centralized architecture**:

- Server → Handles authentication (RADIUS) + IoT services  
- Wireless Router → Provides connectivity & security (WPA2 Enterprise)  
- Switch → Connects server and client  
- IoT Devices → Fan, Light, Door, Window, Garage Door  
- Client Device → Used to monitor and control devices  

---

## 🔐 Security Implementation
- Uses **WPA2-Enterprise** instead of WPA2-Personal  
- Each device has **unique username & password**  
- Authentication is handled by **RADIUS server**  
- Prevents unauthorized access to the network  

---

## ⚙️ Implementation Steps
1. Configure server with static IP  
2. Enable and configure **AAA (RADIUS)** service  
3. Configure wireless router (SSID + WPA2 Enterprise)  
4. Add IoT devices with unique credentials  
5. Setup IoT server for device registration  
6. Access and control devices via web interface  

---

## 🧪 Testing & Verification
- ✅ Connectivity Testing (Network communication)  
- ✅ Authentication Testing (Valid/Invalid login)  
- ✅ Device Control Testing (ON/OFF operations)  

---

## 📊 Features
- Secure device authentication  
- Centralized IoT control  
- Wireless communication  
- Real-time device monitoring  
- Simulation using Cisco Packet Tracer  

---

## ⚠️ Limitations
- Implemented in a simulation environment  
- No real hardware integration  
- No mobile application support  

---

## 🚀 Future Scope
- Integration with real IoT hardware  
- Mobile app for remote access  
- Cloud-based control system  
- Voice assistant integration (AI-based control)  

---

## 👨‍💻 Authors
- Vishal Yadav  
- Suyash Singh  

---

## 📚 References
- Cisco Packet Tracer Documentation  
- IEEE Papers on IoT Security  
- RFC 2865 (RADIUS Protocol)  
- WPA2 Security Guidelines  

---

## 📌 Conclusion
This project successfully demonstrates a **secure smart home system** using IoT and enterprise-level authentication. It highlights the importance of **strong security mechanisms** in modern connected environments.

---
