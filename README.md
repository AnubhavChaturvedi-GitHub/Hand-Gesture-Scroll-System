### README.md

# Hand Gesture Controlled Scrolling

This project uses OpenCV and MediaPipe to recognize hand gestures for controlling the scrolling action on a computer. The gesture recognition is done through the webcam feed, detecting the index and middle fingers' positions to determine the scrolling direction.

## Features
- Detects hand landmarks using MediaPipe
- Recognizes scrolling gestures (up and down) based on the relative positions of the index and middle fingers
- Controls the scrolling action using PyAutoGUI

## Requirements
- Python 3.11.4
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/hand-gesture-controlled-scrolling.git
   cd hand-gesture-controlled-scrolling
   ```

2. Install the required Python packages:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```sh
   python hand_gesture_scrolling.py
   ```

2. The script will open a window showing the webcam feed. Use the following gestures to control the scrolling:

   - Bring your index and middle fingers close together to initiate scrolling.
   - Move your index finger above the middle finger to scroll up.
   - Move your index finger below the middle finger to scroll down.

3. Press `q` to exit the application.

## How it Works

1. The script captures the webcam feed and processes each frame using OpenCV.
2. MediaPipe is used to detect hand landmarks and identify the index and middle finger tips.
3. The Euclidean distance between the index and middle fingers is calculated to detect the scroll gesture.
4. Based on the relative positions of the fingers, PyAutoGUI performs the scrolling action.

## Notes
- Adjust the scrolling increment and threshold values as needed for a better user experience.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

### requirements.txt

```txt
opencv-python
mediapipe
pyautogui
numpy
```### README.md

# Hand Gesture Controlled Scrolling

This project uses OpenCV and MediaPipe to recognize hand gestures for controlling the scrolling action on a computer. The gesture recognition is done through the webcam feed, detecting the index and middle fingers' positions to determine the scrolling direction.

## Features
- Detects hand landmarks using MediaPipe
- Recognizes scrolling gestures (up and down) based on the relative positions of the index and middle fingers
- Controls the scrolling action using PyAutoGUI

## Requirements
- Python 3.7 or higher
- OpenCV
- MediaPipe
- PyAutoGUI
- NumPy

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/hand-gesture-controlled-scrolling.git
   cd hand-gesture-controlled-scrolling
   ```

2. Install the required Python packages:

   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```sh
   python hand_gesture_scrolling.py
   ```

2. The script will open a window showing the webcam feed. Use the following gestures to control the scrolling:

   - Bring your index and middle fingers close together to initiate scrolling.
   - Move your index finger above the middle finger to scroll up.
   - Move your index finger below the middle finger to scroll down.

3. Press `q` to exit the application.

## How it Works

1. The script captures the webcam feed and processes each frame using OpenCV.
2. MediaPipe is used to detect hand landmarks and identify the index and middle finger tips.
3. The Euclidean distance between the index and middle fingers is calculated to detect the scroll gesture.
4. Based on the relative positions of the fingers, PyAutoGUI performs the scrolling action.

## Notes
- Adjust the scrolling increment and threshold values as needed for a better user experience.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

### requirements.txt

```txt
opencv-python
mediapipe
pyautogui
numpy
```
