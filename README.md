# 🏏 Augmented Reality Cricket Game

**COMSATS University Islamabad, Attock Campus - Pakistan (SPRING, 2025)**

---

## 👨‍💻 Authors
- Durr-e-Adan (CIIT/FA21-BAI-005/ATK)
- Syed Ali Raza (CIIT/FA21-BAI-051/ATK)
- Muhammad Hanzala (CIIT/FA21-BAI-010/ATK)

## 🧑‍🏫 Supervisor
- Dr. Farhan Aadil, Associate Professor, Department of Computer Science, COMSATS University Islamabad, Attock Campus

---

## 📄 Project Summary

This project introduces an **Augmented Reality (AR) Cricket Game** that blends a dynamic AR experience with real-time decision-making powered by **Artificial Intelligence (AI)**. Players interact with virtual cricket elements—stadium, pitch, bat, ball—superimposed on the real world using an AR-enabled Android smartphone.

At its core, the system uses AR plane detection for placing a 3D stadium. It features intelligent batsman and bowler agents trained via Python's `RandomForestRegressor` model to make real-time gameplay predictions (e.g., shot types, bowling variations).

---

## ✨ Key Features

### 🔹 Augmented Reality Integration
- Dynamic stadium placement via AR plane detection
- Real-time surface mapping and motion sensing

### 🤖 AI-Powered Opponents
- Batsman and bowler agents using `RandomForestRegressor`
- Dynamic decision-making based on real-time ball context

### 🎮 Gameplay Mechanics
- Batting/bowling side switching
- Gesture-based interaction and physics
- Stadium environment switching and AI-driven bowling

### 🧑‍💻 User Experience
- Score alerts and interactive spatial UI

---

## 🧱 System Architecture

### 📱 Frontend (Client)
- Unity-based Android app for AR rendering and interaction

### 🌐 Backend (Server)
- Python Flask API serving ML predictions and handling HTTP requests

---

### 🧩 Modules

1. **UI Module** – In-game overlays, buttons
2. **AR Module** – Surface detection, stadium placement
3. **AI Module** – Machine learning logic for shot/bowl prediction
4. **Physics Module** – Realistic ball-bat collisions, animations
5. **Audio-Visual Module (Future Scope)** – Sound and visual effects

---

## 🧰 Technologies Used

- **Game Engine:** Unity 2020.3.20f1
- **AR SDKs:** AR Foundation, Google ARCore, Vuforia SDK
- **AI/ML:** Python 3.x, Scikit-learn (`RandomForestRegressor`)
- **Backend:** Flask (Python)
- **Interaction Toolkit:** XR Interaction Toolkit
- **Development Environment:** Google Colab (for ML)

---

## 🚀 Deployment

- **Client:** Android APK (Android 8.0+, ARCore support, 4GB+ RAM)
- **Backend Server:** Flask (deployable via AWS/Render, Gunicorn & Nginx)
- **Storage:** Firebase
- **Distribution:** Google Play Store (planned)

---

## 🔮 Future Work

- Multiplayer (LAN or cloud)
- Voice command features (e.g., "Play Shot", "Bowl Now")
- More advanced batting/bowling variations
- Realistic stadium visuals (crowd, lighting, sound)
- Improved model performance and API latency

---

## 🙏 Acknowledgements

We are genuinely grateful to our supervisor, **Dr. Farhan Aadil**, and co-supervisor **Mr. Bilal Haider** for their invaluable guidance. We thank the faculty of the Department of Computer Science at COMSATS University Attock Campus, and are especially thankful to our families and friends for their constant support.

---

## ❤️ Dedication

**This project is dedicated to our parents.**  
We are deeply grateful to our parents whose unwavering support, prayers, and encouragement have been the foundation of our journey. Their constant belief in our abilities, emotional strength during challenging phases, and sacrifices made behind the scenes have played a crucial role in the successful completion of this project. Without their love and continuous motivation, this achievement would not have been possible. We sincerely thank them from the bottom of our hearts.

---
