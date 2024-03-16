# Gesture Tracking using ESP32-CAM and Controlling the Mouse Pointer

This project utilizes an ESP32-CAM module to track hand gestures through a live video feed. The detected hand gestures are then used to control the mouse pointer on a computer screen.

## Requirements
- Python 3.x
- OpenCV (cv2)
- Numpy
- Autopy
- [Hand Tracking Module](https://github.com/in-explicable/gesture-tracking-using-esp32-cam) (Make sure to replace the link with the actual link to your hand tracking module)

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
2. Install the required Python dependencies:
pip install opencv-python numpy autopy

## Usage
1. Connect your ESP32-CAM module and ensure it's accessible via Wi-Fi.
2. Update the url variable in the Python script with the IP address and port of your ESP32-CAM module.
3. Run the Python script:
  `python gesture_tracking.py`

## How It Works
1. The ESP32-CAM module streams live video over Wi-Fi.
2. OpenCV captures the video feed from the ESP32-CAM.
3. Hand tracking is performed using a pre-trained hand detection model.
4. Based on detected hand gestures, the mouse pointer is controlled accordingly.
5. Index finger up - Moving Mode: Move the mouse pointer based on finger movement.
6. Index and middle fingers up - Clicking Mode: Click the mouse if fingers are close together.

## Contributing
Contributions are welcome! If you want to improve this project, feel free to submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
https://www.youtube.com/watch?v=xjuTEowOWvo&t=54s
