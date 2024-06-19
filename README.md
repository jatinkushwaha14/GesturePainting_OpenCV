# Gesture Painting with OpenCV and MediaPipe

This repository contains a gesture-based painting application built with Python using OpenCV and MediaPipe. The application allows users to draw on a virtual canvas using hand gestures captured via a webcam.

## Features

- **Gesture-Based Drawing**: Draw on a canvas by moving your hand in front of the camera.
- **Color and Brush Selection**: Choose different colors and brush sizes using on-screen buttons.
- **Real-time Frame Rate**: Displays the frame rate of the video capture.

## Requirements

- Python 3.7+
- OpenCV
- MediaPipe
- NumPy

## Usage

1. **Run the Notebook**:
   - Open the Jupyter notebook `GesturePainting.ipynb`.
   - Run all the cells to start the application.

2. **Using the Application**:
   - A window will open showing the webcam feed.
   - Use the top part of the screen to select the brush color.
   - Use the left part of the screen to select the brush size or clear the canvas.
   - Draw on the rest of the screen by moving your hand.

## Controls

- **Colors**:
  - Blue, Green, Red, White (left to right)
- **Brush Sizes**:
  - 10, 30, 50 (top to bottom)
- **Clear Canvas**:
  - Bottom of the left side

## Gesture Instructions

- **Selection**:
  - **Pinch Gesture**: Pinch your thumb and index finger together and move to the desired selection (color or brush size). This gesture is used to make a selection on the UI.
  
- **Drawing**:
  - **Index Finger**: To draw on the canvas, extend only your index finger. Move it across the screen to draw.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project uses [OpenCV](https://opencv.org/) and [MediaPipe](https://mediapipe.dev/).
