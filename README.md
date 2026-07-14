# MemeCam 📸🎭

MemeCam is a fun, interactive real-time webcam application that uses AI to detect your hand gestures and facial expressions, instantly popping up popular memes on your screen based on your actions!

Built with **Python**, **OpenCV**, and **Google MediaPipe** (FaceMesh & Hands), MemeCam tracks your face and hands to recognize a variety of custom gestures and triggers specific meme images when a match is found.

## Features
- **Real-Time AI Tracking:** Fast and lightweight face and hand landmark detection using MediaPipe.
- **Dynamic Calibration:** Calibrates to your neutral face shape automatically during the first few seconds of startup to ensure accurate facial expression detection.
- **Gesture-Based Memes:** Translates iconic real-life poses into their corresponding internet memes.
- **Minimalist HUD:** Displays real-time hand gesture status and current active meme on the camera feed.
<img width="1361" height="602" alt="mem" src="https://github.com/user-attachments/assets/f19ac8ab-c768-4144-a90f-9f48712b0e2c" />

## Supported Memes & Gestures
Here are the current memes supported and the gestures you need to perform to trigger them:

### 🖐️ One-Handed Gestures
- **Success Kid (`kid.jpg`)**: Raise a single closed fist (all fingers closed).
- **Hehehe Lizard (`hehe.jfif`)**: Show a "shaka" or surfer sign (only your pinky open, other fingers closed).
- **Confused / What (`what.jfif`)**: Raise one hand fully open (all 4 fingers extended).
- **Roll Safe / Think About It (`nigga.png`)**: Point your index finger and touch/keep it very close to your eye or temple.
- **Rat (`rata.jpeg`)**: Show a peace sign (index and middle fingers open, others closed).

### 👐 Two-Handed Gestures
- **Sonic (`Sonic.jpeg`)**: Raise both hands with index fingers pointing up, and keep your hands above your nose level.
- **Cara / Khaby Lame (`cara.jpeg`)**: Both hands fully open, held apart from each other, in the lower half of the camera view.
- **Cristiano (`cristiano.png`)**: Point both index fingers towards your mouth.

### 😲 Facial Expressions
- **Cat (`gato1.png`)**: Open your mouth wide and stick your tongue out (lower your chin).
- **Dog (`perro.jpeg`)**: Raise your eyebrows playfully.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/MemeCam.git
   cd MemeCam
   ```

2. **Install the required dependencies:**
   Make sure you have Python installed. You can install the required libraries using pip:
   ```bash
   pip install opencv-python mediapipe numpy
   ```

3. **Ensure you have the meme images:**
   Make sure all the `.jpeg`, `.jpg`, `.jfif`, and `.png` meme image files are located in the same directory as `main.py`.

## Usage

Run the main script:
```bash
python main.py
```

**Calibration Phase:** 
When you first start the app, a progress bar will appear. Look straight into the camera with a **neutral face** until the bar reaches 100%. This helps the app calibrate to your specific facial features.

After calibration, try out the gestures listed above to see the memes pop up in the separate "Meme Detectado" window!

Press `ESC` to exit the application.
