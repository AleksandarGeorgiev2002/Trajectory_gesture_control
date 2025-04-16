Trajectory Gesture Control
This is a simple Python project that lets you control actions using hand-drawn gestures tracked via a webcam. The idea is to draw shapes or paths in the air, and the system recognizes them based on their trajectory.

What It Does
Tracks your hand in real-time using your webcam

Records the path you draw with your finger

Compares it to saved gestures and runs actions based on matches

You can add your own custom gestures

How to Run
1. Clone the repo
bash
Copy
Edit
git clone https://github.com/AleksandarGeorgiev2002/Trajectory_gesture_control.git
cd Trajectory_gesture_control
2. Install dependencies
Make sure you have Python 3.7+ and run:

bash
Copy
Edit
pip install opencv-python numpy matplotlib
3. Start the app
bash
Copy
Edit
python HandTrackingLogicStartEndPoint.py
That’s it — your webcam will open, and you can start testing gestures.

Files
HandTrackingLogicStartEndPoint.py: Main script to run the app

HandTrackingLogicStartEndPoint_2.ipynb: Jupyter notebook version for testing/debugging

.idea/: IDE settings (can be ignored)

Notes
You can modify the code to define your own gestures and link them to any actions you want.

The matching is based on the trajectory/shape you draw, not on exact position.
