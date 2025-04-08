# Hand Gesture Detection

This project focuses on detecting hand textures as an initial step toward implementing hand gesture-based control for hardware systems. The solution utilizes MediaPipe and OpenCV to detect and process hand landmarks in real time. These landmarks will serve as the foundation for recognizing gestures and triggering corresponding actions in future development stages.

## How This Code Works:
Hand Landmark Detection: MediaPipe detects the hand landmarks in the camera feed.
1. Gesture Rules: We define two gestures:
2. Fist Gesture: When the thumb is the highest landmark and the other fingers are below it.
3. Thumbs Up Gesture: When the thumb is higher than the other fingers.
4. Gesture Display: The program displays the gesture detected in the window (Fist Gesture, Thumbs Up, or No Gesture).

## Running the Program
Code is <a herf="Hand_gesture_detection.ipynb">here!</a>
1. Install the required libraries, run the following commands:
    ```
    pip install opencv-python
    pip install mediapipe
    ```
2. Clone GitRepo and nevigate to the file.
3. Run below command.
    ```
    python hand_gesture_detection.py
    ```

## <u>Video demostration</u>
[![DemostrationVideo](https://img.youtube.com/vi/Gm_105isvc8/0.jpg)](https://www.youtube.com/watch?v=Gm_105isvc8)

<br><br><br>

---
🧑‍💻 *Developed by Jayashanka Anushan*  
📧 Email: [jayasankaanushan199@gmail.com](mailto:jayasankaanushan199@gmail.com)  
🌐 [Portfolio](https://sites.google.com/view/jayashanka-anushan/home) | [LinkedIn](https://linkedin.com/in/JayashankaAnushan) | [GitHub](https://github.com/JayashankaAnushan)
