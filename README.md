# Air-Fruit-Ninja 🍉 
A browser-based, hand gesture-controlled "Fruit Ninja" clone that uses AI to turn your hand into a blade. No mouse or touch required—just slice the air!

🛠️ The Tech Stack:

1. MediaPipe Hands: Used for real-time 2D/3D hand landmark detection. It tracks 21 points on the hand to calculate the precise position of your index finger tip.
2. HTML5 Canvas API: Handles the high-performance rendering of fruit physics, particle explosions (splashes), and the "slash" trail effects.
3. JavaScript (ES6+): The core engine managing the game state, gravity physics, and collision detection algorithms.
4. Google Fonts: Utilizes 'Permanent Marker' and 'Bebas Neue' for that classic arcade aesthetic.

✨ Key Features:

1. Real-time Gesture Tracking: High-speed tracking with minimal latency using your webcam.
2. Dynamic Difficulty: The game gets faster and spawns more fruits as the 60-second timer counts down.
3. Combo System: Slice multiple fruits in a single horizontal swipe to multiply your score.
4. Visual Feedback: Haptic-style visual splashes and screen shakes (vignette) for an immersive experience.

📖 How to Run Locally

1. Clone this repository.
2. Open index.html using a local server (like Live Server in VS Code).
3. Ensure your webcam is connected and you are in a well-lit environment.

Note: Must be served over HTTPS or localhost for camera permissions to work!
