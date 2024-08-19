
# Hand Tracking and Screen Control

The project will demonstrate hand tracking with screen control using Python. This will make use of the MediaPipe library, which enables hand detection and OpenCV for image processing. On the other hand, PyAutoGUI shall be used to move the mouse cursor according to the position of the hand.

## Features

- **Hand Tracking**: Utilizes MediaPipe to detect and track hand landmarks in real-time.
- **Mouse Control**: Maps hand position to screen coordinates to control the mouse cursor.
- **Real-Time Display**: Displays the video feed with hand landmarks and FPS in real-time.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

## Installation

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/hand-tracking-screen-control.git
    cd hand-tracking-screen-control
    ```

2. **Install Dependencies:**

    Create a virtual environment and install the required packages:

    ```bash
    pip install opencv-python mediapipe pyautogui
    ```

## Usage

1. **Run the Script:**

    Execute the script using Python:

    ```bash
    python hand_tracking_screen_control.py
    ```

2. **Operation:**

    - **Hand Tracking**: The script captures video from the webcam and tracks hand landmarks.
    - **Mouse Control**: The position of the index finger (landmark ID 1) is mapped to the screen coordinates to move the mouse cursor.

## Code Overview

- **Video Capture**: Captures video feed from the webcam using OpenCV.
- **Hand Detection**: Processes the video feed to detect hand landmarks with MediaPipe.
- **Cursor Movement**: Maps hand position to screen coordinates using PyAutoGUI.
- **FPS Display**: Shows the frames per second (FPS) on the video feed.



---

Replace the placeholder GitHub link with your actual repository URL and adjust any other details as needed!
