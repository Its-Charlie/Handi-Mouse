# Handimouse

A gesture-controlled virtual mouse that lets users control their cursor using hand movements captured through a webcam. Built using Python, OpenCV, and MediaPipe, this project provides hands-free interaction ideal for accessibility and creative human-computer interaction.

## Packages Required:
``` bash
pip install opencv-python
pip install mediapipe
pip install pyautogui
pip install numpy
pip install opencv-contrib-python
```
## Features:
- Hand Tracking using MediaPipe
Detects hand landmarks in real-time using your webcam.
- Cursor Control via Finger Movements
The index finger controls the mouse pointer smoothly.
- Left Click Gesture
Performed when the index finger and thumb come close.
- Right Click Gesture
Triggered using a different finger combination.
- Scrolling Feature
Scrolls the screen based on hand movement (up/down).
- Distance-based Gesture Recognition
Measures fingertip distances to execute actions.
- Real-time Visualization
Displays detection window with hand landmarks.
- Fully Hands-Free Interaction
No hardware needed except a webcam.

## Gestures Used in Handi-Mouse:

***Right Hand Gestures:-***
- Move index finger → Move mouse cursor
- Thumb + Index finger pinch → Right click
- Thumb + Middle finger pinch → Enable/disable scroll mode
- Move middle finger up/down (while in scroll mode) → Scroll up/down
- Thumb + Ring finger pinch → Start/stop selection (drag)
- Thumb + Pinky finger pinch → Copy (Ctrl + C)
- Thumb + Index + Middle finger pinch → Paste (Ctrl + V)

***Left Hand Gestures:-***
- Thumb + Index finger pinch → Left click
- Thumb + Middle finger pinch → Enable/disable zoom mode
- Move middle finger up/down (while in zoom mode) → Zoom in/out

