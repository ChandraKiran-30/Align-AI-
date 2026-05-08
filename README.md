# AlignAI 🏋️‍♂️

### Personal Training, Perfected by AI

AlignAI is a browser-based AI fitness assistant that provides real-time posture correction and workout feedback using computer vision and pose estimation models. The application helps users improve exercise form, reduce injury risk, and train more effectively without requiring wearables or external hardware.

---

# 🚀 Problem Statement

Incorrect workout posture is one of the major causes of gym injuries and ineffective training. Personal trainers can help, but they are often expensive and inaccessible for many users.

AlignAI addresses this problem by providing instant AI-driven posture correction using only a device camera, enabling safer and more effective workouts anytime and anywhere.

---

# 💡 Solution Overview

AlignAI uses real-time pose estimation and posture analysis to:

* Detect body joints and movement patterns through the device camera
* Calculate joint angles during exercises
* Compare user posture against predefined ideal exercise form
* Provide immediate visual and audio feedback for correction
* Track workout performance and form accuracy

---

# 🔁 System Workflow

```text
Camera Input → Pose Detection → Posture Analysis → Error Detection → Instant Feedback → User Correction
```

### Workflow Breakdown

1. **Camera Input**

   * Captures live user movements through the browser camera.

2. **Pose Detection**

   * Detects body landmarks and skeletal points in real time.

3. **Posture Analysis**

   * Computes joint angles and compares posture with predefined exercise standards.

4. **Error Detection**

   * Identifies incorrect posture and movement deviations.

5. **Feedback System**

   * Displays visual overlays and triggers audio alerts for incorrect form.

6. **Correction Loop**

   * Allows users to instantly adjust posture during workouts.

---

# ✨ Key Features

## ✅ Real-Time Posture Correction

Provides live posture analysis with visual skeleton overlays and joint tracking.

## 🔊 Audio Feedback Alerts

Instant beep alerts notify users whenever incorrect form is detected.

## 📷 No Wearables Required

Uses only a browser camera for fully automated posture monitoring.

## 🧠 AI-Based Pose Estimation

Leverages computer vision and deep learning models for body tracking and movement analysis.

## 📊 Performance Tracking

Tracks workout metrics such as:

* Repetition count
* Session duration
* Form accuracy

---

# 🛠️ Technology Stack

## Frontend

* HTML5
* CSS3
* JavaScript (ES6)

## AI & Pose Estimation

* TensorFlow.js (MoveNet)
* MediaPipe BlazePose

## Visualization & Feedback

* HTML Canvas
* Web Audio API

## Storage

* Browser LocalStorage

---

# ⚙️ Implementation Summary

* Captured live video feed using browser camera APIs
* Applied pose estimation models for real-time body landmark detection
* Computed body joint angles for exercise posture validation
* Implemented rule-based posture correction logic
* Generated visual and audio feedback for posture errors
* Stored workout performance metrics locally for session analysis

---

# 🎯 Future Enhancements

* Support for additional exercises and workout routines
* Personalized workout feedback using historical session data
* Mobile and standalone application deployment
* AI-powered adaptive correction models
* Integration with physiotherapy and fitness guidance systems

---

# 🌍 Vision & Impact

AlignAI aims to democratize access to intelligent fitness guidance by making posture correction accessible to everyone.

The platform helps:

* Reduce workout injuries
* Improve exercise effectiveness
* Build consistent fitness habits
* Enable safer workouts without personal trainers

---

# 👥 Team GymGenius

* Surampally Poojitha
* Shraddha Desaraju
* Rohan Reddy
* Rohit Kothari
* Neelam Chandra Kiran

---

# 📄 License

This project is intended for educational and research purposes.

---

> “The resistance that you fight physically in the gym and the resistance that you fight in life can only build a strong character.”
>
> — Arnold Schwarzenegger
