# 🖱️ Eye Controlled Mouse using Python, OpenCV & MediaPipe

A Python-based Eye Controlled Mouse system that uses your **eye movement** to move the mouse cursor and **blinking** to perform mouse clicks. Built using `MediaPipe`, `OpenCV`, and `PyAutoGUI`.

![Eye Controlled Mouse](https://user-images.githubusercontent.com/yourimageplaceholder.png) <!-- Replace with actual image/GIF link if available -->

---

## 🚀 Features

- ✅ Control your mouse cursor using **eye gaze direction**
- 👁️ Detect eye **blinks to trigger mouse clicks**
- 🎯 Real-time face & eye tracking with **MediaPipe FaceMesh**
- 🧠 Works with standard webcam (no special hardware required)

---

## 📦 Tech Stack

| Library     | Description                           |
|-------------|---------------------------------------|
| `cv2`       | OpenCV for video capture & rendering  |
| `mediapipe` | FaceMesh model for facial landmarks   |
| `pyautogui` | Simulates mouse movements & clicks    |

---

## 🖥️ How It Works

1. **Face Detection:** Uses MediaPipe's FaceMesh to detect facial landmarks.
2. **Iris Tracking:** Tracks iris (landmarks 474–478) to control mouse pointer.
3. **Blink Detection:** Monitors distance between eye-lid landmarks (145, 159) to detect blinks.
4. **Mouse Interaction:** Blinks trigger clicks using PyAutoGUI.

---

## 📸 Demo

> *(Include a GIF or video demo here if available)*

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/eye-controlled-mouse.git
cd eye-controlled-mouse
pip install opencv-python mediapipe pyautogui
