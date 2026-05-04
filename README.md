# ✋ Real-Time Hand Tracking using MediaPipe & OpenCV

## 🧠 Overview

This project is a **real-time hand tracking system** that detects and visualizes hand landmarks using a webcam.
It utilizes **MediaPipe Hands** to accurately track hand movements and draw connections between key points.

The system processes live video and overlays a skeletal structure of the detected hand.

---

## 🚀 Features

* 🎥 Real-time webcam hand detection
* 🖐️ Detection of 21 hand landmarks
* 🔗 Drawing hand connections (skeleton)
* ⚡ Fast and efficient tracking using MediaPipe
* 🎯 Works for single or multiple hands

---

## 🛠️ Technologies Used

* Python 🐍
* OpenCV (Video Processing)
* MediaPipe (Hand Tracking & Landmark Detection)

---

## 📂 Project Structure

```id="g7k2lm"
├── app.py
└── README.md
```

---

## ▶️ How to Run

### 1. Install Dependencies

```bash id="h3k9pz"
pip install opencv-python mediapipe
```

### 2. Run the Application

```bash id="u2x8qn"
python app.py
```

---

## 🎯 How It Works

* The webcam captures live video frames
* Frames are converted from BGR to RGB format
* MediaPipe processes each frame to detect hands
* If a hand is detected:

  * 21 landmark points are identified
  * Landmarks are connected to form a hand skeleton

---

## 📸 Output

* Displays real-time video feed
* Overlays hand landmarks and connections on detected hands

---

## 💡 Use Cases

* Gesture recognition systems 🤖
* Virtual mouse / keyboard control 🖱️
* Sign language recognition ✍️
* Augmented Reality (AR) applications 🎮

---

## 💡 Future Improvements

* Add gesture classification model
* Control system actions using hand gestures
* Track finger movements for drawing applications 🎨
* Deploy as a web-based application

---

## 👨‍💻 Author

**Youssef Ayman**
AI Engineer & Data Scientist

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
