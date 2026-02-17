# My-Project
For my resume

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


[Balance Robot](https://github.com/otto6147/Balance-Robot)
