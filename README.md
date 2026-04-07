🌌 Neon Air Draw — AI Spatial Interface

A fast, real-time AI-powered air drawing web app that uses advanced hand tracking to create a futuristic “Minority Report”-like spatial experience.

Draw in the air with your dominant hand and control your creations in real-time with your other hand using natural gestures like Move, Scale, and Rotate.

✨ Key Features
✋ Dual-Hand Control:
Right Hand (Dominant): Used for precise drawing, erasing specific parts, and clearing the canvas.
Left Hand (Secondary): Handles spatial transformations such as moving, scaling, and rotating strokes.
📐 Non-Destructive Transformations:
Strokes keep their original coordinates intact. All transformations (translation, scaling, rotation) are applied during rendering using matrix operations.
🕶️ Sleek Glassmorphism UI:
A clean, modern interface with a glass-like aesthetic, featuring real-time HUD elements and visual feedback.
⚡ Optimized Performance:
Built on a WebGL rendering engine to ensure smooth 60FPS interactions.
🌀 Physics-Driven Motion:
Includes smooth inertia effects and rotation snapping at 45° angles for better control.
📖 Gesture Guide:
Comes with an interactive guide explaining all gestures and controls.
🛠️ Tech Stack
Frontend: React + Vite
Hand Tracking: @mediapipe/hands
Animations: Framer Motion
Icons: Lucide React (with custom SVG fallbacks)
Styling: Vanilla CSS (Glassmorphism + Neon theme)
🎮 Gesture Manual
✍️ Drawing Hand (Right Hand)
Gesture	Action
☝️ Index Up	Begin drawing
🤏 Pinch	Erase selectively (based on fingertip path)
✊ Fist	Clear entire canvas
🖐️ Control Hand (Left Hand)
Gesture	Action	Visual Feedback
✌️ Two Fingers	Move nearest stroke	Blue crosshair + glow
🤏 Pinch & Spread	Scale stroke	Rings + percentage indicator
🤚 Open Palm	Rotate stroke	Orange arc + snap markers
🚀 Getting Started

Install Dependencies:

npm install

Start Development Server:

npm run dev
Run the App:
Allow camera access and bring your hands into view to start interacting.

Crafted with passion for AI and spatial computing.