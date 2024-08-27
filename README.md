# Virtual Mouse Using AI

This project implements a virtual mouse using computer vision techniques and hand-tracking with AI. The system uses a webcam to capture real-time video, detects hand landmarks using MediaPipe, and controls the mouse cursor based on hand gestures.

## Features

- **Hand Tracking**: The system detects and tracks hand movements using MediaPipe.
- **Cursor Control**: The index finger's position controls the mouse cursor's movement.
- **Clicking**: The user can perform a mouse click by bringing the thumb and index finger close together.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

## Installation

1. Clone this repository or download the script.
2. Install the required Python packages:

   ```bash
   pip install opencv-python mediapipe pyautogui
   ```

## Usage

1. Run the Python script:

   ```bash
   python virtual_mouse.py
   ```

2. The webcam will open, and the system will start tracking your hand. Move your index finger to control the mouse cursor. Bring your thumb close to the index finger to simulate a mouse click.

## How It Works

- The script uses OpenCV to capture video from the webcam and process each frame.
- MediaPipe is used to detect hand landmarks in the frame.
- The coordinates of the index finger and thumb are mapped to the screen dimensions.
- PyAutoGUI controls the mouse cursor based on the hand's position and performs clicks when the thumb and index finger are close together.

## Contributing

Feel free to fork this repository and contribute by adding more features or improving the existing ones. Pull requests are welcome!

## License

This project is open-source and available under the [MIT License](LICENSE).

