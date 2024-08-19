Hand Tracking and Screen Control
The project will demonstrate hand tracking with screen control using Python.
This will make use of the MediaPipe library, which enables hand detection and OpenCV for image processing.
On the other hand, PyAutoGUI shall be used to move the mouse cursor according to the position of the hand.

Features
Hand Tracking: Utilizes MediaPipe to detect and track hand landmarks in real-time.
Mouse Control: Maps hand position to screen coordinates to control the mouse cursor.
Real-Time Display: Displays the video feed with hand landmarks and FPS in real-time.
Requirements
Python 3.x
OpenCV
MediaPipe
PyAutoGUI
Installation
Clone the Repository:

Copy code
git clone https://github.com/yourusername/hand-tracking-screen-control.git
cd hand-tracking-screen-control
Install Dependencies:

Create a virtual environment and install the required packages:

Copy code
pip install opencv-python mediapipe pyautogui
Usage
Run the Script:

Execute the script using Python:


Copy code
python hand_tracking_screen_control.py
