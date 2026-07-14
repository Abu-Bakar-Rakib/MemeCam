# 📸 MemeCam

<p align="center">
  <img src="assets/banner.gif" width="100%" alt="MemeCam Banner">
</p>

<p align="center">
  <strong>AI-Powered Real-Time Meme Detection Using Hand Gestures & Facial Expressions</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg">
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg">
  <img src="https://img.shields.io/badge/MediaPipe-AI%20Tracking-orange.svg">
  <img src="https://img.shields.io/badge/Real--Time-30FPS-success.svg">
  <img src="https://img.shields.io/badge/Status-Active-purple.svg">
  <img src="https://img.shields.io/github/stars/Abu-Bakar-Rakib/MemeCam?style=social">
</p>

---

## 🎭 Overview

**MemeCam AI** is an interactive computer vision application that transforms your webcam into an intelligent meme machine.

Powered by **OpenCV**, **MediaPipe**, and **Python**, the system analyzes hand gestures and facial expressions in real time, automatically triggering context-aware meme reactions. Whether you're flashing a peace sign, raising your eyebrows, pointing at your temple, or sticking out your tongue, MemeCam instantly detects the action and displays the perfect meme.

This project combines modern AI-powered landmark tracking with internet culture to create a fun, engaging, and highly interactive experience.

---

## ✨ Features

### 🤖 AI-Powered Detection
- Real-time face landmark tracking
- Real-time hand landmark tracking
- Dual-hand gesture recognition
- Facial expression analysis
- Face-hand interaction detection
- Adaptive confidence smoothing

### 🎯 Smart Calibration
- Automatic facial calibration during startup
- Personalized expression thresholds
- Improved accuracy across users
- Robust detection in different environments

### 🖐️ Gesture Recognition Engine
Supports:
- Single-hand gestures
- Dual-hand gestures
- Facial expressions
- Combined face + hand interactions

### 📊 Live HUD Interface
- Current detected gesture
- Active meme status
- Hand state visualization
- Detection feedback system

### ⚡ Real-Time Performance
- Low latency processing
- Lightweight architecture
- Optimized MediaPipe pipeline
- Smooth webcam interaction

---

# 🎬 Supported Meme Reactions

## 🖐️ Single-Hand Gestures

| Gesture | Meme |
|----------|----------|
| ✊ Closed Fist | Success Kid |
| 🤙 Shaka Sign | Hehehe Lizard |
| ✋ Open Hand | Confused / What |
| 👁️ Point to Eye | Roll Safe |
| ✌️ Peace Sign | Rat |

---

## 🙌 Dual-Hand Gestures

| Gesture | Meme |
|----------|----------|
| ☝️ Both Hands Raised | Sonic |
| 👐 Open Hands Apart | Khaby Lame |
| 👉 Fingers Toward Mouth | Cristiano Ronaldo |

---

## 😀 Facial Expressions

| Expression | Meme |
|------------|------------|
| 👅 Tongue Out | Cat |
| 🤨 Raised Eyebrows | Dog |

---

# 🧠 AI Detection Pipeline

```text
Webcam Input
      │
      ▼
MediaPipe Face Mesh
      │
      ├── Facial Expression Analysis
      │
      ▼
MediaPipe Hand Tracking
      │
      ├── Single-Hand Detection
      ├── Dual-Hand Detection
      └── Face-Hand Interaction
      │
      ▼
Gesture Classification
      │
      ▼
Meme Selection Engine
      │
      ▼
Real-Time Meme Display
```

---

# 📸 Demo

<p align="center">
  <img src="https://github.com/user-attachments/assets/f19ac8ab-c768-4144-a90f-9f48712b0e2c" width="900">
</p>

---

# 🛠️ Technology Stack

| Technology | Purpose |
|------------|----------|
| Python | Core Development |
| OpenCV | Image Processing |
| MediaPipe | Face & Hand Tracking |
| NumPy | Numerical Computation |

---

# 📦 Installation

## Clone the Repository

```bash
git clone https://github.com/Abu-Bakar-Rakib/MemeCam.git

cd MemeCam
```

## Install Dependencies

```bash
pip install opencv-python mediapipe numpy
```

Or install from requirements file:

```bash
pip install -r requirements.txt
```

---

# ▶️ Running MemeCam

```bash
python main.py
```

---

# 🎯 Calibration Process

When MemeCam starts:

1. Look directly at the webcam.
2. Maintain a neutral facial expression.
3. Keep your face centered.
4. Remain still for a few seconds.

The application will automatically calibrate your facial features to improve expression recognition accuracy.

---

# 🎮 Controls

| Key | Action |
|------|---------|
| ESC | Exit Application |

---

# 📂 Project Structure

```text
MemeCam/
│
├── main.py
├── README.md
├── requirements.txt
│
├── kid.jpg
├── hehe.jfif
├── what.jfif
├── rata.jpeg
├── Sonic.jpeg
├── cara.jpeg
├── cristiano.png
├── gato1.png
└── perro.jpeg
```

---

# 📈 Performance

| Metric | Value |
|----------|----------|
| Face Tracking | Real-Time |
| Hand Tracking | Up to 2 Hands |
| Camera Resolution | 640×480+ |
| Target FPS | 30 FPS |
| Detection Latency | < 200 ms |

---

# 🚀 Future Improvements

- [ ] Custom Meme Packs
- [ ] User-Defined Gesture Mapping
- [ ] Sound Effects & Audio Reactions
- [ ] Deep Learning Gesture Classification
- [ ] Multi-Person Support
- [ ] Streamlit Web Version
- [ ] Meme Statistics Dashboard
- [ ] Custom Training Mode

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add AmazingFeature"
```

4. Push to GitHub

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

# 📜 License

This project is provided for educational, research, and entertainment purposes.

---

# ⭐ Support

If you enjoyed this project, consider giving it a **Star ⭐** on GitHub.

Your support helps the project reach more developers, researchers, and meme enthusiasts.

---

<p align="center">
  <b>Built with ❤️ using Python, OpenCV, MediaPipe, and Memes 🎭</b>
</p>
