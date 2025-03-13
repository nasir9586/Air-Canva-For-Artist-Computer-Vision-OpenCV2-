# Air Canvas for Artists

## Introduction
The **Air Canvas for Artists** project leverages **computer vision** and **machine learning** to enable users to draw in the air using their fingers. Using **OpenCV** and **Mediapipe**, this project detects hand landmarks and tracks finger movements to create digital drawings. It is an innovative and interactive project, making it a valuable addition to the resume of **machine learning** and **computer vision** enthusiasts.

This project is implemented in **Python** due to its extensive libraries and easy-to-use syntax, but it can be adapted to any language supported by OpenCV.

## Algorithm
1. **Frame Capture & Processing**: Read frames from the webcam and convert them to **HSV color space** for better color detection.
2. **Canvas Setup**: Prepare a drawing canvas and add ink selection buttons.
3. **Hand Detection Initialization**: Configure **Mediapipe** to detect a single hand.
4. **Landmark Detection**: Process frames through the **Mediapipe Hand Detector** to identify hand landmarks.
5. **Track Finger Movement**: Extract the coordinates of the forefinger and store them in an array for successive frames.
6. **Drawing on Canvas**: Use the stored points to draw on the screen, allowing users to sketch in the air.

## Features
- **Real-Time Hand Tracking**: Uses **Mediapipe** to detect and track hand movements.
- **Air Drawing**: Allows drawing in the air using finger movements.
- **Multiple Ink Colors**: Switch between different colors using UI buttons.
- **Canvas Erase Option**: Clear the screen with a predefined gesture.
- **Efficient Performance**: Optimized for real-time execution with minimal latency.

## Future Enhancements
- Adding gesture-based undo and redo functionality.
- Implementing shape recognition for drawing predefined shapes.
- Enhancing UI with additional customization features.
