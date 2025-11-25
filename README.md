# ECOPAGER-main-repository
#-Smart Paperless Examination System

EcoPager is an IoT + Mobile + Cloud based smart examination solution created to reduce paper waste, lower administrative costs, and modernize the examination process in educational institutions.

This project integrates:
- ESP32-based smart devices
- Android mobile applications
- Firebase backend
- Admin controlled exam management
- Paperless MCQ-driven examination system

**Project Leader & System Architect:** Fehmida Ashraf

---

## 🌍 Problem Statement

Every year, millions of trees are cut to produce paper for MCQ sheets used in schools, colleges, board exams, and entry tests. These papers are used only once and thrown away, causing massive environmental damage.

**EcoPager** addresses this problem by replacing traditional MCQ answer sheets with a low-cost, rechargeable, touch-based smart device and an integrated mobile system that performs:

- Exam distribution  
- Student registration  
- Answer collection  
- Automatic result generation  

With this system, **paper consumption and manpower are drastically reduced.**

---

## 💡 Solution Overview

EcoPager is composed of **2 smart devices + 2 mobile applications + 1 cloud backend**:

### 1. Student Device (ESP32 + TFT Screen)
- Displays MCQ-based examination paper
- Allows answer selection via touchscreen
- Answer cannot be changed once selected
- Submits paper automatically after timer completion
- Works on rechargeable battery

### 2. Admin / Teacher Device
- Receives exam paper from mobile app
- Sends paper to student devices using Bluetooth / WiFi
- Collects student answers after submission

### 3. Student Android Application
- Student registration in exam center
- Receives roll number and exam details
- Provides practice MCQs with instant result
- Shows roll number slip digitally

Repo:  
➡ **https://github.com/FehmidaAshraf/EcoPager**

---

### 4. Admin / Teacher Android Application
- Student enrollment management
- Roll number assignment
- MCQ paper creation
- Sends paper to student devices
- Receives student responses
- Generates final result

Repo:  
➡ **https://github.com/FehmidaAshraf/EcoPager-X**

---

### 5. Student Device Code (IoT / Embedded System)
Handles student device firmware using ESP32 and TFT.

Repo:  
➡ **https://github.com/leeqa/Ecopager**

---

### 6. Admin / Teacher Device Firmware
Handles admin-side device for paper transmission and data collection.

Repo:  
➡ **https://github.com/leeqa/Ecopager-Arduino-Admin**

---

## 🧠 My Role & Contribution

I served as the **Team Leader and Main Developer**:

- Designed the complete system architecture
- Connected devices + apps + Firebase
- Built backend using:
  - Firebase Authentication
  - Firebase Realtime / Firestore Database
  - Notifications
- Implemented:
  - User registration & enrollment flow
  - Roll number assignment system
  - Data syncing / result calculation logic
- Managed project coordination and version control
- Prepared technical documentation with diagrams

*UI/UX and app design were handled by other team members.*

---

## 🔧 Technologies Used

| Area | Technologies |
|------|-------------|
| Embedded Systems | ESP32, Arduino IDE, TFT Display |
| Mobile Apps | Android (Java) |
| Backend | Firebase Auth, Firestore/Realtime DB |
| Communication | Bluetooth, WiFi |
| Tools | GitHub, Android Studio, Firebase Console |

---

## 📊 Key Advantages

✔ 100% Paperless system  
✔ Low power – no computers required  
✔ Portable & rechargeable devices  
✔ Reduces manpower  
✔ Auto result generation  
✔ Eco-friendly & scalable  

---

## 📁 Project Documentation

Complete report including:
- Architecture Diagram  
- Sequence Diagrams  
- Use Case Diagrams  
- App Screenshots  
- Hardware Model  
- Workflow Explanation  

Will be added in:  
`/docs/EcoPager_X_Final_Documentation.pdf`

*You may also add a Google Drive link here if needed.*

---

## 📈 Future Scope

- AI-based cheating detection
- Multi-language system
- Large scale testing in institutions
- Exam encryption & enhanced security
- Cloud dashboard for analytics

---

## 📌 Conclusion

EcoPager proves that with low-cost embedded hardware, efficient software integration and cloud computing, large-scale examination systems can be transformed into a fast, reliable and eco-friendly solution.

This project represents real-world innovation in **green computing and digital transformation**.

---

📩 Developed and Led by: **Fehmida Ashraf**  
🌐 GitHub: https://github.com/FehmidaAshraf
