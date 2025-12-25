# 🎄 Christmas Tree

Hello! This is a small experimental project created to celebrate Christmas. ✨  

It started as a simple idea: drawing a regular 3D Christmas tree.  
But that felt too ordinary—so it was enhanced with **hand gesture recognition** and **particle effects**.

You can now control the tree *in mid-air* using your webcam and even hang your favorite photos on it.

Despite being only a few hundred lines of code, the visual impact is strong—especially on large screens.

👉 **Live Demo (Cross-platform supported):**  
https://christmas-tree-hand-gestures.vercel.app

<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/45f3ec57-00b5-4989-b3b2-484772ad95cf" />


## 🤔 What Is This? (Intro)

This is not a static holiday greeting page.  
It is a **dynamic Christmas tree composed of thousands of particles**.

By integrating **Google MediaPipe**, the tree understands your hand gestures in real time.

### Features
- Particle Effects
- Gesture Control via Webcam
- Photo Uploads as Floating Polaroids
- Minimalist Black & Gold Design

---

## 🛠️ Tech Stack
Pure frontend magic—no heavy frameworks involved:
- Three.js - 3D rendering and particle system
- MediaPipe – Real-time hand gesture recognition
- Vanilla JavaScript (ES Modules) – Core logic and interaction

---

## 🎮 Controls (How to Play)
For the best experience, turn on your speakers
(no background music yet—but Jingle Bells is highly recommended 🎵).

### 🖐️ Gesture Mode (Main Feature)
Make sure camera access is allowed, then:
- Open Palm (🖐️): Activates Explosion Mode.
The tree disperses into particles and allows free rotation.
- Closed Fist (✊): Regroups all particles back into the Christmas tree.
- Pinch Gesture (🤏): Randomly selects a photo and enlarges it, as if you’re grabbing it.

### 🖱️ Mouse Controls
- Left-click drag to rotate
- Mouse wheel to zoom
- Press H to hide all UI (perfect for screenshots or screen recordings)

---

## 🚀 How to Run Locally

⚠️ Important:
Because this project uses ES Modules and camera permissions,
do NOT open index.html directly (double-clicking will cause CORS errors).
You must run it via a local server.

### Recommended: VS Code
- Install the Live Server extension
- Right-click index.html
- Select “Open with Live Server”

### Python
```bash
python -m http.server 8000
```

### Node.js
```bash
npx serve
```

## 📱 Mobile Support

Mobile web support included.

## Contributors
[![Contributors](https://img.shields.io/github/contributors/ErnestChainDev/Christmas-Tree?color=dark-green)](https://github.com/ErnestChainDev/Christmas-Tree/graphs/contributors)
