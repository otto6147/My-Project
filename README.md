# My-Project
For my resume

## [Network Design](https://github.com/otto6147/My-network-design/blob/main/README.md)

# Basic Network Topology & Routing

### **Cisco Packet Tracer | Networking Fundamentals**

โปรเจกต์จำลองเครือข่ายพื้นฐาน (Star Topology) ที่ประกอบด้วยหลายวงเครือข่าย เพื่อสาธิตการทำงานของ Default Gateway และการรับ-ส่งข้อมูลข้ามวงแลน (Inter-Subnet Connectivity) ให้สามารถสื่อสารกันได้จริง

---

### **Key Highlights**

* **Multi-Subnet Architecture:** แบ่งเครือข่ายออกเป็นหลายวง (LAN 1, LAN 2) เพื่อจำลองโครงสร้างองค์กรเบื้องต้น
* **Inter-Subnet Routing:** การตั้งค่าขา Interface บน Router เพื่อทำหน้าที่เป็นทางผ่านของข้อมูล (Gateway)
* **Plug & Play Design:** เน้นความเข้าใจเรื่องการเชื่อมต่อทางกายภาพและการกำหนด IP Address โดยไม่มีการตั้งค่าความปลอดภัยที่ซับซ้อน
* **Connectivity Verification:** ทดสอบความถูกต้องของเครือข่ายด้วยคำสั่ง Ping และระบบ Simulation Mode

### **Network Components**

* **Router:** ทำหน้าที่เป็นตัวกลางเชื่อม Subnet (Inter-VLAN / Static Routing)
* **Switches:** กระจายสัญญาณไปยังอุปกรณ์ปลายทางในแต่ละแผนก
* **End Devices:** เครื่อง PC และ Laptop สำหรับทดสอบการรับ-ส่งข้อมูล
* **Addressing:** ใช้การกำหนดหมายเลขแบบ Static IP เพื่อความง่ายในการศึกษา






## [Dust Detect](https://github.com/otto6147/Dust-detect)

### Smart Air Quality & Automation System

###### IoT Monitoring | ESP8266 | Firebase | Node-RED

ระบบตรวจวัดคุณภาพอากาศอัจฉริยะที่เชื่อมต่อ Cloud เพื่อตรวจสอบค่าฝุ่น (PM1.0, PM2.5, PM10) และสภาพแวดล้อม (Temp/Humid) แบบ Real-time พร้อมระบบสั่งการอุปกรณ์ไฟฟ้า (Relay) อัตโนมัติผ่านการตั้งค่าเกณฑ์วัดจาก Dashboard

### Key Features
- **Real-time Monitoring**: ติดตามค่าฝุ่นละออง PM1.0, PM2.5, PM10 และสภาพอากาศ (DHT22) ได้ทันที

- **Cloud Synchronization**: เชื่อมต่อกับ Firebase Realtime Database เพื่อเก็บข้อมูลและรับคำสั่ง

- **Smart Control**: ควบคุม Relay 2 ช่องทางอัตโนมัติ ตามเงื่อนไขที่ตั้งค่าผ่าน Node-RED

- **Auto-reconnect**: มีระบบกู้คืนการเชื่อมต่อ WiFi และ Firebase อัตโนมัติหากสัญญาณหลุด


### Tech Stack

- **Hardware**: ESP8266 (NodeMCU), PMS3003 Sensor, DHT22, Relay Module

- **Cloud/Backend**: Firebase Realtime Database

- **Frontend/Logic**: Node-RED (Dashboard & Threshold Control)

- **Language**: C++ (Arduino IDE)


# [Balance Robot](https://github.com/otto6147/Balance-Robot)


# Self-Balancing Robot (PID Control)

### **Arduino | MPU6050 | PID Algorithm | IR Control**

โปรเจกต์หุ่นยนต์สองล้อทรงตัวอัตโนมัติที่ผสานการทำงานระหว่างเซนเซอร์วัดความเฉื่อย (IMU) และการประมวลผลทางคณิตศาสตร์แบบ PID เพื่อรักษาความสมดุลในแนวตั้ง พร้อมรองรับการสั่งงานเคลื่อนที่ผ่านรีโมทคอนโทรลแบบไร้สาย

---

### **Key Highlights**

* **Active Balancing:** ใช้เซนเซอร์ **MPU6050** (Gyroscope + Accelerometer) ตรวจจับมุมเอียงแบบ Real-time
* **PID Stability:** ควบคุมการทรงตัวด้วยอัลกอริทึม **PID Control** ที่มีความแม่นยำสูง ลดการแกว่งและรักษาจุดสมดุล
* **Wireless Control:** สั่งการเดินหน้า-ถอยหลัง และเลี้ยวซ้าย-ขวา ผ่าน **IR Remote**
* **Dynamic Response:** ระบบปรับความเร็วมอเตอร์อัตโนมัติผ่านสัญญาณ PWM เพื่อสู้กับแรงโน้มถ่วง

### **Tech Stack**

* **Controller:** Arduino Nano / Uno
* **Sensing:** MPU6050 (6-Axis Motion Tracking)
* **Actuation:** DC Gear Motors + L298N Motor Driver
* **Communication:** Infrared (IR) Receiver
* **Language:** C++ (Arduino Sketch)

