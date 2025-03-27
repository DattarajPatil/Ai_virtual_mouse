# Gesture-Based Control System

## Overview
This project implements a gesture-based control system using computer vision and hand tracking. It utilizes OpenCV, MediaPipe, and PyAutoGUI to recognize hand gestures and perform actions such as mouse control, volume adjustment, screen brightness control, and scrolling.

## Features
- Hand gesture recognition using MediaPipe
- Mouse movement and click control
- Volume and brightness adjustment
- Vertical and horizontal scrolling
- Multi-hand detection and classification

## Dependencies
To run this project, you need the following Python libraries:

```sh
pip install opencv-python mediapipe pyautogui screen-brightness-control pycaw google protobuf comtypes
```

## How It Works
- Uses MediaPipe to detect hand landmarks.
- Classifies gestures based on finger positions.
- Maps gestures to actions like cursor movement, clicking, scrolling, or adjusting system settings.

### Gesture Mappings
| Gesture | Action |
|---------|--------|
| Open palm | Cursor movement |
| Fist | Mouse drag |
| Index finger up | Right-click |
| Two fingers up | Left-click |
| Two fingers closed | Double-click |
| Pinch (major) | Adjust brightness/volume |
| Pinch (minor) | Scroll |

## Running the Program
To start the gesture control system, simply run the script:
```sh
python gesture_control.py
```

## Exit Instructions
To exit the application, press the `Enter` key.

## Future Improvements
- Adding more gesture mappings
- Enhancing detection accuracy
- Support for additional system controls

## Author
Dattaraj Patil

---
Feel free to contribute and improve this project!

