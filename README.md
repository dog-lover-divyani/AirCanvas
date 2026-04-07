# 🌌 AirCanvas — AI Spatial Drawing Interface

A high-performance, real-time AI-powered air drawing web application that uses advanced hand tracking to create a futuristic spatial interaction experience.

Draw freely in the air with your dominant hand and manipulate your creations in real-time using intuitive gestures like Move, Scale, and Rotate.

## ✨ Key Features

- ✋ Dual-Hand Interaction  
  - Dominant Hand: Precise drawing, selective erasing, full canvas clearing  
  - Secondary Hand: Move, Scale, Rotate  

- 📐 Non-Destructive Transform System  
  - Original stroke data is preserved  
  - Transformations applied dynamically using matrix operations  

- 🕶️ Modern Glassmorphism UI  
  - Minimal, clean interface  
  - Real-time HUD and visual feedback  

- ⚡ High Performance Rendering  
  - WebGL-powered engine  
  - Smooth 60FPS interactions  

- 🌀 Physics-Based Interaction  
  - Smooth inertia effects  
  - 45° snap rotation  

- 📖 Built-in Gesture Guide  
  - Interactive manual for gestures  

## 🛠️ Tech Stack

- Frontend: React + Vite  
- Hand Tracking: @mediapipe/hands  
- Animations: Framer Motion  
- Icons: Lucide React + custom SVG  
- Styling: Vanilla CSS  

## 🎮 Gesture Manual

### ✍️ Drawing Hand (Dominant)

- ☝️ Index Up → Start drawing  
- 🤏 Pinch → Selective erase  
- ✊ Fist → Clear canvas  

### 🖐️ Control Hand (Secondary)

- ✌️ Two Fingers → Move stroke  
- 🤏 Pinch & Spread → Scale stroke  
- 🤚 Open Palm → Rotate stroke  

## 🚀 Getting Started

### 1. Install Dependencies
```bash
npm install
```
### 2. Run the App
```bash
npm run dev
```

### 3. Use
- Allow camera access
- Bring hands into view
- Start drawing

### 📌 Future Improvements
- Multi-user collaboration
- Export drawings (PNG/SVG)
- Custom gesture mapping
- Mobile support

### 🤝 Contributing
Feel free to fork and submit a pull request.


---

⚠️ Important: When pasting inside your main README, don’t wrap this whole thing again in triple backticks — just paste it directly.


### Direct Link

https://air-canvas-six.vercel.app/
