# 🖐️ Hand Finger Counter using Python & OpenCV

This is a computer vision project that detects **a single hand** from a webcam feed and **counts the number of fingers** being shown in real-time. The system uses **OpenCV** along with **MediaPipe** (or a custom hand tracking module) to detect landmarks on the hand and calculate how many fingers are extended.

> ✅ Works even when multiple hands are present – it processes only the **first detected hand**.

---

## 📌 Features

- Real-time webcam capture
- Hand landmark detection
- Finger counting (0 to 5 fingers)
- Robust tracking with background tolerance

---

## ⚙️ Requirements

- Python 3.7+
- OpenCV
- MediaPipe (or custom hand landmark module)

---

## 🧰 Installation

```bash
git clone https://github.com/your-username/hand-finger-counter.git
cd hand-finger-counter
pip install opencv-python mediapipe
