# Real-Time Hand Detection

A lightweight Python script (`hands_detect.py`) that performs real-time hand tracking and landmark detection using your computer's webcam. This project leverages Google's **MediaPipe** framework for robust machine learning solutions and **OpenCV** for image processing and rendering.

## 🚀 Features

* **Real-Time Tracking:** Processes video feed from your primary webcam instantly.
* **Multi-Hand Support:** Detects and tracks up to 2 hands simultaneously.
* **Precise Landmarks:** Maps 21 distinct 3D landmarks (knuckles, fingertips, palm base) on each detected hand.
* **Selfie-View:** Automatically mirrors the video output horizontally for an intuitive user experience.



## 🛠️ Prerequisites

Before running the script, ensure you have Python installed on your system along with the necessary libraries.

You will need the following Python packages:
* `opencv-python` (cv2)
* `mediapipe`

## 📥 Installation

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone [https://github.com/jinnping/hand_detection.git](https://github.com/jinnping/hand_detection.git)
   cd hand_detection
