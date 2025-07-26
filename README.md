🖐️ Hand Gesture Mouse Control Using OpenCV, MediaPipe & PyAutoGUI
Control your mouse using hand gestures through your webcam!
This project uses MediaPipe for real-time hand tracking and PyAutoGUI to simulate mouse movements and clicks.

📽️ Demo
Coming Soon – Include a GIF or link to a video demo here!

🚀 Features
🖱️ Move cursor using your index finger

👆 Tap with two fingers to left-click

✌️ Tap with three fingers to double-click

👋 Calibration system to adapt to different lighting and hand sizes

📌 Preview window that stays always on top for convenience

🎯 Smooth cursor movement using a built-in smoothing algorithm

🛠️ Tech Stack
Component	Library
Hand Tracking	MediaPipe
Mouse Control	PyAutoGUI
GUI Handling	OpenCV
Windows Control	pygetwindow, pywin32

📦 Requirements
Install dependencies using:

bash
Copy
Edit
python -m pip install --upgrade opencv-python mediapipe pyautogui pygetwindow pywin32
Ensure you're using Python 3.7 – 3.11 for MediaPipe compatibility.

🧠 How It Works
📌 Calibration Phase (first 5 seconds)
Hold one finger up and move it to each corner of your screen.

This helps calibrate movement space for accurate mapping.

🖱️ Gesture Mappings
Gesture	Fingers Up	Action
👉 Move	1	Cursor follows finger
✌️ Click	2	Left Click
🤟 Double Click	3	Double Click

Thumb is counted only if clearly extended sideways.

🖥️ Running the App
bash
Copy
Edit
python gesture_control.py
Controls:

Show right hand with one finger to control cursor.

Show two or three fingers to click/double-click.

Press q to exit.

⚠ Known Issues
Performance may vary depending on webcam quality.

In low light or cluttered backgrounds, tracking might be unstable.

Only the right hand is supported (filtered by handedness detection).

💡 Tips
Use a bright, neutral background for better detection.

If cursor behaves oddly, restart the app to recalibrate.

Want to add right click or scrolling? It’s easy – open an issue or contribute!

🧑‍💻 Author
Your Name
Made with ❤️ using Python, OpenCV & MediaPipe
GitHub: your-github-profile

📄 License
MIT License
