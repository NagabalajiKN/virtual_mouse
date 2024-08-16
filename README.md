# Hand Gesture Control Using Mediapipe and OpenCV

## 🔥 Overview
This project implements a hand gesture control system using computer vision techniques. By utilizing **Mediapipe** for hand tracking and **OpenCV** for video processing, the program allows users to control their computer via hand gestures captured from a webcam.

## 🎯 Objective
The main goal of this project is to create a touchless interaction system where users can control their system's actions like volume control, cursor movement, screenshots, and media controls (e.g., space, left/right arrow keys) using hand gestures.

## ⚙️ Features
- **Cursor Control:** Move the mouse pointer with hand gestures.
- **Volume Control:** Adjust the system volume based on the distance between hands.
- **Media Controls:** Play/Pause (spacebar), skip forward (right arrow), skip backward (left arrow), and more using specific hand gestures.
- **Screenshots:** Take a screenshot by performing a designated hand gesture.
  
## 🛠️ Technologies Used
- **Python**
- **Mediapipe** (for hand landmark detection)
- **OpenCV** (for video capture and image processing)
- **PyAutoGUI** (for simulating keyboard and mouse actions)
- **PyCaw** (for controlling system audio)

## 🏗️ Project Workflow
1. **Initialize Video Capture:** Captures real-time video from the webcam.
2. **Hand Detection & Landmark Extraction:** Detects hand landmarks using Mediapipe and draws connections between them.
3. **Gesture Recognition:** Various hand gestures are identified based on the position of specific landmarks.
4. **Action Execution:** Actions like cursor movement, volume control, media control, and screenshots are performed based on the recognized gestures.

## 🚀 How to Run the Project
Follow these steps to set up and run the project on your local machine:

### Prerequisites
Make sure you have the following libraries installed:
- `mediapipe`
- `opencv-python`
- `numpy`
- `pyautogui`
- `pycaw`

You can install them using pip:

  `pip install mediapipe opencv-python numpy pyautogui pycaw`

## ✋ Gesture Actions
Here are some examples of the hand gestures and their corresponding actions:

- **All Fingers Open:** Presses `space` (Play/Pause).
- **Index Finger and Pinky Up:** Presses the `right arrow` (Next).
- **Index and Middle Finger Up:** Presses the `left arrow` (Previous).
- **Three Fingers Up:** Presses `up arrow` (Volume Up).
- **Index Finger Pointing:** Controls the mouse cursor.
- **Thumb and Pinky Touch:** Takes a screenshot.

## 🎧 Volume Control
The distance between the landmarks of your hands determines the system's volume level. The further apart your hands are, the louder the volume becomes.

## 📷 Screenshots
Perform a specific hand gesture (like making a fist with the index finger extended) to trigger a screenshot and save it to the current working directory.

## 🎨 Future Improvements
- Improve gesture recognition accuracy.
- Add support for more hand gestures to control different actions.
- Implement a user interface to customize gestures and actions.



