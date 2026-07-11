<div align="center">

# 🚗 DriCare360
### AI-Powered Driver Monitoring & Drowsiness Detection System

<p align="center">
An intelligent computer vision solution that enhances road safety by detecting driver fatigue, distraction, and drowsiness in real time using facial landmark analysis.
</p>

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red?logo=streamlit)
![Dlib](https://img.shields.io/badge/Dlib-Facial%20Landmarks-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

---

# 📖 Overview

**DriCare360** is an AI-powered Driver Monitoring System developed to improve road safety by continuously monitoring a driver's alertness using computer vision techniques.

The application analyzes **Eye Aspect Ratio (EAR)**, **Mouth Aspect Ratio (MAR)**, and **Head Pose Estimation (Yaw Angle)** from a live webcam feed to identify signs of fatigue and distraction. Whenever unsafe driving behavior is detected, the system instantly triggers an **audio alarm**, sends an **email notification** to the registered emergency contact, and securely records the event for future analysis.

The project demonstrates the practical application of Artificial Intelligence and Computer Vision in intelligent transportation systems.

---

# ✨ Key Features

✔️ Real-Time Driver Monitoring

✔️ Eye Blink & Eye Closure Detection (EAR)

✔️ Drowsiness Detection

✔️ Yawning Detection (MAR)

✔️ Head Pose & Distraction Detection

✔️ Instant Audio Alert System

✔️ Automatic Email Notifications

✔️ Event Logging with Timestamp

✔️ Secure Login & Registration

✔️ Interactive Streamlit Dashboard

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Computer Vision | OpenCV |
| Face Detection | Dlib |
| Web Framework | Streamlit |
| Numerical Computing | NumPy |
| Scientific Computing | SciPy |
| Image Processing | Imutils |
| Data Handling | Pandas |
| Notification Service | SMTP Email |

---

# ⚙️ System Workflow

```text
Live Webcam
      │
      ▼
Face Detection (Dlib)
      │
      ▼
Facial Landmark Extraction
      │
      ▼
EAR • MAR • Head Pose Analysis
      │
      ▼
Driver State Classification
      │
      ├───────────────┐
      ▼               ▼
Audio Alert      Email Notification
      │               │
      └──────► Event Logging ◄──────┘
```

---

# 📂 Project Modules

### 👤 Authentication
- User Registration
- Secure Login
- Profile Management

### 🚘 Driver Monitoring
- Face Detection
- Eye Tracking
- Blink Detection
- Yawning Detection
- Head Pose Estimation

### 🚨 Alert System
- Real-Time Audio Alarm
- Automatic Email Alerts

### 📊 Dashboard
- Driver Monitoring Interface
- Activity Logs
- Alert History

---

# 📸 Application Preview

> Replace these placeholders with screenshots.

| Login | Dashboard |
|-------|-----------|
| Add Screenshot | Add Screenshot |

| Live Monitoring | Alert Detection |
|-----------------|-----------------|
| Add Screenshot | Add Screenshot |

---

# 🚀 Future Enhancements

- 📱 Android Application
- ☁ Cloud Database Integration
- 📍 GPS Location Tracking
- 🤖 Deep Learning-Based Detection
- 👨‍👩‍👧 Multi-Driver Support
- 📈 Driver Analytics Dashboard
- 📹 CCTV Integration
- 🚑 Emergency SMS & WhatsApp Alerts

---

# 💻 Installation

Clone the repository

```bash
git clone https://github.com/your-username/DriCare360.git
```

Move into the project directory

```bash
cd DriCare360
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

# 📁 Project Structure

```
DriCare360
│
├── app.py
├── requirements.txt
├── assets/
├── models/
├── screenshots/
├── utils/
├── README.md
└── shape_predictor_68_face_landmarks.dat
```

---

# 🎯 Applications

- Smart Vehicles
- Fleet Management
- Commercial Transportation
- Logistics Industry
- Driver Safety Systems
- Research & Academic Projects

---

# 👨‍💻 Developed By

## **Anuj Dhiraj Kochar**

**Computer Science Engineering Student**

Passionate about Artificial Intelligence, Machine Learning, Computer Vision, Data Analytics, and Full-Stack Development.

---

<div align="center">

### ⭐ If you like this project, consider giving it a Star!

Made with ❤️ using Python & Computer Vision

</div>
