# Hand Gesture Brightness Control 🖐️💡

A real-time computer vision application built with Python, OpenCV, and MediaPipe that tracks hand landmarks via webcam to dynamically control screen brightness using pinch gestures.

---

## 📌 Features
- **Real-Time Hand Tracking:** Detects hand landmarks instantly using MediaPipe Hands.
- **Dynamic Gesture Control:** Maps the distance between your thumb tip and index finger tip directly to display brightness levels ($0\% - 100\%$).
- **Visual Feedback UI:** Displays a live percentage meter and level bar overlaid on the webcam feed.
- **Cross-Platform Monitor Support:** Uses `screen-brightness-control` to adjust brightness across laptop screens and supported external monitors.

---

## 🛠️ Tech Stack
- **Python 3.8+**
- **OpenCV** (Video capture & image rendering)
- **MediaPipe** (Hand landmark estimation)
- **NumPy** (Mathematical distance mapping)
- **screen-brightness-control** (OS screen brightness control)

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python installed on your system.

### 2. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/hand-gesture-brightness-control.git](https://github.com/YOUR_USERNAME/hand-gesture-brightness-control.git)
cd hand-gesture-brightness-control
