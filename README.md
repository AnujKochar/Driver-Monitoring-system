<<<<<<< HEAD
# 🚗 DriCare360 – Driver Monitoring System

**DriCare360** is a smart driver safety solution built to monitor a driver’s alertness and detect early signs of drowsiness using facial landmark analysis. The system leverages a webcam to analyze **eye closure (EAR)**, **yawning (MAR)**, and **head tilts (yaw angle)** in real time. If signs of drowsiness are detected, DriCare360 initiates **audio alerts** and **sends email notifications** to the driver’s emergency contact.

---

## 🧠 Key Highlights

- ✅ Built using **Streamlit** for a user-friendly interface
- ✅ Analyzes live webcam feed with facial landmark detection
- ✅ Detects closed eyes, yawns, and head tilts using EAR, MAR, and yaw
- ✅ Sends **automatic alerts** via email to prevent accidents
- ✅ Maintains user profiles and logs each drowsiness event with a timestamp
- ✅ Secured login/register system for personalized experience

---

## 🗂️ Project Structure

```
.
├── assets/                        # Audio & static assets
├── db/                            # SQLite databases for users and logs
├── modules/                       # Facial feature detection scripts
│   ├── EAR.py                     # Eye Aspect Ratio logic
│   ├── MAR.py                     # Mouth Aspect Ratio logic
│   ├── headpose.py                # Head pose detection (yaw)
├── app.py                         # Main Streamlit GUI
├── main.py                        # Drowsiness monitoring backend
├── notifier2.py                   # Email notifier
├── SQL.py                         # DB operations (login, events, contacts)
├── utils.py                       # Utility functions
├── requirements.txt               # Required packages
├── shape_predictor_68_face_landmarks.dat  # Dlib model for landmark detection
=======
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
>>>>>>> 0a8fda580942bfd65dbea12e5f1ab3c6a34a4802
```

---

<<<<<<< HEAD
## 📥 Required File

👉 **Download:** [shape_predictor_68_face_landmarks.dat](https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat)  
After extracting, place the `.dat` file in your root directory.

This file is essential for facial landmark detection and must be included for the system to function properly.

---

## 🚦 How to Use
=======
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
>>>>>>> 0a8fda580942bfd65dbea12e5f1ab3c6a34a4802

```bash
streamlit run app.py
```

<<<<<<< HEAD
Once launched, the app provides:
- 🔐 Login or registration page
- 👤 User detail & emergency contact form
- 👁️ Start Detection – Live monitoring with EAR, MAR & yaw tracking
- 📜 View logs of past drowsiness detection events

---

## ⚙️ System Features

### 🧍‍♂️ User Authentication
- Secure login and registration system
- Stores user details in a database

### 👨‍👩‍👧‍👦 Family Contact Management
- Add or update emergency contact details
- Used for sending alerts during drowsy states

### 👁️ Drowsiness Detection
- **EAR**: Detects eye closure duration
- **MAR**: Identifies yawning patterns
- **Yaw Angle**: Head pose estimation

### 🚨 Multi-level Alerts
- Plays audio warnings for short drowsiness
- Sends email alerts if drowsiness persists

### 🕒 Event Logging
- Timestamped records of every alert event
- View past logs in a tabular UI inside the app

---

## 🔧 Requirements

- Python 3.9
- dlib
- OpenCV
- Streamlit
- numpy
- scipy
- pandas
- imutils
- sqlite3 (builtin)
- smtplib (builtin)

---

## 👥 Project Credit

This project, DriCare360, was developed as a group academic submission.
While the collaboration involved shared ideas and planning, the complete implementation—including UI design, backend logic, feature integration —was independently carried out by Rupali Shewale.

=======
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
>>>>>>> 0a8fda580942bfd65dbea12e5f1ab3c6a34a4802
