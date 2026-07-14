# MemeCam 📸🎭

A real-time AI-powered webcam application that detects hand gestures and facial expressions to trigger contextually relevant meme overlays. Built with Python, OpenCV, and Google MediaPipe for fast, accurate computer vision processing.

---

## Overview

MemeCam is an interactive desktop application that leverages modern computer vision and machine learning to recognize human gestures and expressions in real-time. The application automatically displays corresponding meme images on your screen based on detected poses and facial cues, creating an engaging and entertaining user experience.

**Key Technologies:**
- Python 3.x
- OpenCV (image processing and display)
- Google MediaPipe (face and hand landmark detection)
- NumPy (numerical computation)

---

## Features

- **Real-Time AI Tracking** – Fast and efficient face and hand landmark detection using MediaPipe's pre-trained models
- **Automatic Calibration** – Self-calibrating neutral face detection during startup to ensure accurate facial expression recognition
- **Gesture Recognition** – Supports 10+ unique gestures and facial expressions across both single-hand and dual-hand interactions
- **Live HUD Display** – On-screen indicators showing detected gesture status and active meme overlay
- **Lightweight & Responsive** – Optimized for real-time performance with minimal latency

![MemeCam Demo](https://github.com/user-attachments/assets/f19ac8ab-c768-4144-a90f-9f48712b0e2c)

---

## Supported Gestures & Memes

### Single-Hand Gestures

| Gesture | Meme | Description |
|---------|------|-------------|
| **Closed Fist** | Success Kid | Raise a single closed fist with all fingers closed |
| **Shaka Sign** | Hehehe Lizard | Show a surfer/shaka sign (pinky extended, others closed) |
| **Open Hand** | Confused / What | Fully open hand with all fingers extended |
| **Index Point to Eye** | Roll Safe / Think About It | Point index finger directly at or very close to your eye or temple |
| **Peace Sign** | Rat | Index and middle fingers extended, others closed |

### Dual-Hand Gestures

| Gesture | Meme | Description |
|---------|------|-------------|
| **Both Hands Up** | Sonic | Both hands raised with index fingers pointing upward, held above nose level |
| **Open Hands Apart** | Cara / Khaby Lame | Both hands fully open and held apart in the lower camera area |
| **Fingers to Mouth** | Cristiano | Both index fingers pointed toward your mouth |

### Facial Expressions

| Expression | Meme | Description |
|------------|------|-------------|
| **Tongue Out** | Cat | Open mouth wide with tongue extended and chin lowered |
| **Raised Eyebrows** | Dog | Playfully raised eyebrows |

---

## Installation

### Prerequisites

- Python 3.7 or higher
- Webcam device
- All meme image files (.jpg, .jpeg, .jfif, .png)

### Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Abu-Bakar-Rakib/MemeCam.git
   cd MemeCam
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
   Or manually install required packages:
   ```bash
   pip install opencv-python mediapipe numpy
   ```

3. **Verify meme assets:**
   Ensure all meme image files are located in the same directory as `main.py`:
   - `kid.jpg`
   - `hehe.jfif`
   - `what.jfif`
   - `nigga.png`
   - `rata.jpeg`
   - `Sonic.jpeg`
   - `cara.jpeg`
   - `cristiano.png`
   - `gato1.png`
   - `perro.jpeg`

---

## Usage

### Running the Application

```bash
python main.py
```

### Calibration Phase

1. Upon startup, a calibration progress bar will appear
2. Face the camera with a **neutral, relaxed expression**
3. Keep your face steady and centered until the calibration reaches 100%
4. This process takes approximately 3-5 seconds and ensures optimal accuracy for your facial features

### Gesture Detection

After calibration completes:
1. Perform any supported gesture or facial expression
2. The detected meme will display in a separate "Meme Detectado" window
3. The HUD will indicate the current recognized gesture

### Exiting

Press `ESC` to exit the application at any time.

---

## Project Structure

```
MemeCam/
├── main.py              # Main application entry point
├── README.md            # This file
├── requirements.txt     # Python dependencies (optional)
├── kid.jpg
 ├── hehe.jfif
 ├── what.jfif
 └── ... (other meme files)
```

---

## Performance Considerations

- **Frame Rate:** Application targets 30 FPS for smooth real-time detection
- **Latency:** Gesture detection typically occurs within 100-200ms of the gesture being performed
- **System Requirements:** Requires a modern CPU; GPU acceleration optional but recommended for better performance
- **Webcam Quality:** Works best with webcams providing 720p or higher resolution

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| **Memes not appearing** | Verify all image files are in the correct directory and file names match exactly |
| **Poor gesture detection** | Ensure proper lighting; complete full calibration with neutral expression |
| **Lag or stuttering** | Close other CPU-intensive applications; check webcam resolution settings |
| **Calibration fails** | Keep your face centered and still during calibration; ensure adequate lighting |

---

## Future Enhancements

- [ ] Custom gesture configuration via JSON config file
- [ ] Additional gesture recognition (e.g., thumbs up, V-sign)
- [ ] Sound effects and audio feedback
- [ ] Gesture combo detection (sequential gestures)
- [ ] Performance metrics and statistics
- [ ] Settings GUI for calibration and sensitivity tuning

---

## License

This project is provided as-is for educational and entertainment purposes.

---

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## Contact & Support

For issues, questions, or suggestions, please open a GitHub Issue or contact the repository maintainer.

---

**Enjoy detecting memes! 🎉**
