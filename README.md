# Virtual Mouse

This project is a Hand Gesture Recognition system designed to control a computer using hand gestures. It leverages computer vision techniques to detect and track hand movements, enabling users to perform various actions like moving the mouse cursor, left-clicking, right-clicking, double-clicking, and scrolling.

## Features

- **Mouse Movement**: Control the cursor position using your index finger.
- **Left Click**: Trigger a left click with a specific hand gesture (index finger up and thumb up).
- **Right Click**: Trigger a right click with a different hand gesture (index and middle fingers up).
- **Double Click**: Perform a double click with another gesture (thumb up).
- **Scrolling**: Scroll up and down using gestures (index, middle, and ring fingers up or all fingers up).

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/HandGestureRecognition.git
    cd HandGestureRecognition
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Ensure you have a working webcam**.

## Usage

1. **Run the main script**:
    ```bash
    python main.py
    ```

2. **Hand Gestures**:
    - **Mouse Movement**: Raise your index finger.
    - **Left Click**: Raise your index finger and thumb.
    - **Right Click**: Raise your index and middle fingers.
    - **Double Click**: Raise your thumb.
    - **Scroll Up**: Raise your index, middle, and ring fingers.
    - **Scroll Down**: Raise all fingers.

3. **Exit the Program**:
    - Press the `x` key.

## Dependencies

- `cv2` (OpenCV)
- `mediapipe`
- `numpy`
- `pyautogui`
- `HandGestureRecognition` (custom module)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)
- [PyAutoGUI](https://pyautogui.readthedocs.io/)

