# Selfie Taker with Face and Smile Detection

This project uses OpenCV to detect faces and smiles in real-time using a webcam. When a smile is detected, the program automatically captures a selfie and saves it with a timestamped filename. The system continuously scans the video feed for faces and smiles until you press the 'q' key to quit.

## Features

- **Face Detection**: Uses Haar Cascade Classifiers to detect faces in real-time from the webcam feed.
- **Smile Detection**: Detects smiles within the region of the detected face using another Haar Cascade Classifier.
- **Automatic Selfie Capture**: When a smile is detected, a selfie is automatically taken and saved with a timestamped filename.
- **Real-time Display**: Shows the live webcam feed with bounding boxes around detected faces and smiles.

## Requirements

- Python 3.x
- Libraries:
  - `opencv-python`: For video capture and image processing.
  
You can install the required libraries using:

```bash
pip install opencv-python
