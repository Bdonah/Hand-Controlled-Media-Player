# P8: Hand-Controlled Media Player Using OpenCV and MediaPipe

This project uses Python, OpenCV, MediaPipe, and PyAutoGUI to create an interactive, hand-controlled media player. By leveraging computer vision and hand tracking, the system enables users to control media playback (e.g., play, pause, adjust volume) using simple hand gestures in real-time.

🔧 Tools and Libraries Used
- Python 3: The core programming language used for writing and executing the project.
- OpenCV: Facilitates webcam access, real-time video processing, and image manipulation to capture and analyze video frames.
- MediaPipe: Provides a pre-trained hand-tracking model for detecting hand landmarks, tracking gestures, and interpreting them in real time.
- PyAutoGUI: Handles system-level automation, such as simulating key presses or mouse movements for controlling media players.

💡How It Works:
The media player operates by capturing live webcam input, tracking hand gestures, and converting them into media control commands. For example, raising specific fingers could trigger volume adjustments or pause/play actions, providing a seamless and touchless interface for interacting with media.

📋 Project Workflow
1. Importing required libraries
2. Initialize MediaPipe drawing utilities and hand solutions
3. IDs of fingertip landmarks as defined in MediaPipe's hand model
4. Variables to store the current gesture state and control actions
5. Set camera resolution
6. Function to extract the positions of hand landmarks
7. Start webcam capture and set resolution
8. Initialize MediaPipe Hands with confidence thresholds
9. Process the frame for hand tracking
10. Draw hand landmarks on the image
11. Get the positions of hand landmarks
12. Count how many fingers are up
13. Media control actions based on finger count and position
14. Exit the loop if the 'q' key is pressed
15. Release resources and close windows

✨ Let’s Collaborate!
I’m always looking for ways to improve my projects and learn from the tech community. If you have suggestions for enhancing the functionality of this hand-controlled media player, or ideas for creative use cases, let’s connect! Feel free to share your thoughts and feedback in the comments below—I’d love to explore new possibilities together! 😊
<img src="https://github.com/iamramzan/Hand-Controlled-Media-Player-Using-OpenCV-and-MediaPipe/blob/main/Hand-Controlled%20Mediaplayer.png">
