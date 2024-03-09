# VisageVision

VisageVision is a simple Python project that utilizes the OpenCV library for real-time face detection using a webcam. The program captures video frames, converts them to grayscale, and detects faces using a Haar Cascade Classifier. Detected faces are then outlined with rectangles and displayed in a window. Additionally, the program saves the output video with annotated faces to a file.

## Dependencies

Make sure you have the following dependencies installed:

- Python 3.x
- OpenCV
- NumPy

You can install the required dependencies using the following command:

```bash
pip install opencv-python numpy
```


## Project Structure

- `face_detection.py`: The main Python script containing the face detection implementation.
- `haarcascade_frontalface_default.xml`: Haar Cascade Classifier for face detection.
- `output.avi`: Output video file with annotated faces.

## Usage

- The program captures video frames from the default camera (usually the built-in webcam).
- Detected faces are outlined with green rectangles.
- Press 'q' to exit the program.

