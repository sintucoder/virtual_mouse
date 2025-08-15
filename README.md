# virtual_mouse
AI-Powered Virtual Mouse 🖱️🤖 A touchless human-computer interaction system that uses MediaPipe and OpenCV to track hand gestures in real-time, enabling smooth cursor movement, left/right clicks, and custom gesture commands — all without touching a physical mouse.

AI-Powered Virtual Mouse 🖱️🤖

I recently built AirCursor, a gesture-controlled virtual mouse that lets you move your cursor, click, and trigger commands — without touching a physical mouse. Using MediaPipe and OpenCV, it tracks your hand in real-time to translate gestures into mouse actions.

🔧 How I built it:
🔹 Used MediaPipe Hands for accurate real-time hand landmark detection
🔹 Integrated OpenCV for video capture & processing
🔹 Added PyAutoGUI for controlling cursor & clicks
🔹 Implemented gesture recognition logic (cursor movement, left/right click, special “YES” gesture)
🔹 Applied smoothening filters for precise control & reduced jitter
🔹 Designed a small always-on-top window for easy monitoring

✨ Features:
✔ Smooth cursor movement with just your index finger
✔ Left click (Thumb + Index touch)
✔ Right click (Thumb + Middle touch)
✔ Special gestures for custom actions
✔ Works in real-time without external hardware
