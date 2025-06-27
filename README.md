# ✋💡 Brightness Control Using Hand Gestures – Python + OpenCV

Control your screen brightness without touching your keyboard or mouse – just move your hand in front of your webcam 😎  
Built using **Python, OpenCV, MediaPipe**, and the **Screen Brightness Control** module.

---

## 📦 What’s Inside?

> Uses real-time hand tracking and calculates the distance between your thumb and index finger to adjust screen brightness accordingly.

---

## 🛠️ Tech Stack

### 🧪 External Libraries:
- `opencv-python`  → for real-time webcam video & image processing  
- `mediapipe` → to detect hand landmarks (by Google)  
- `screen-brightness-control` → to control brightness of your screen  
- `numpy` → for calculations and interpolation

```bash
pip install opencv-python
pip install mediapipe
pip install screen-brightness-control
pip install numpy
```

### 📚 Built-in Libraries:
- `math` → to calculate distance between fingers

---

## 🎬 Demo Video


<video width="700" controls autoplay loop>
  <source src="demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

---

## 📸 How It Works (Concept)

1. Hand landmarks (thumb tip & index tip) detected using MediaPipe  
2. Distance between them is measured  
3. Mapped to brightness range using interpolation  
4. Brightness gets updated in real time!

---

## 💬 Suggestions?

Open an issue or DM me if you want help setting this up or customizing it for your device!

---
