# Face Detection Project

This project focuses on face detection using OpenCV and the Mediapipe library. It detects faces in both videos and images and provides bounding box annotations along with confidence scores.

## Description

The Face Detection project utilizes OpenCV and the Mediapipe library to detect faces in videos and images. The Mediapipe Face Detection API is used to locate faces, and bounding boxes are drawn around the detected faces. Additionally, the confidence scores of the detections are displayed.

## Features

- Face Detection in videos and images
- Bounding box annotations for detected faces
- Display of confidence scores for each detection
- Frames per second (FPS) calculation

## Files

The project consists of the following files:

- `face_detection_basics.py`: Detects faces in a provided video file using the Mediapipe Face Detection API. Bounding boxes are drawn around the detected faces, and confidence scores are displayed. The script also calculates and displays the frames per second (FPS).

- `face_detection_module.py`: Contains a reusable class called `FaceDetector` that encapsulates the functionality of face detection using Mediapipe. The class provides a `findFaces()` method that takes an image as input and returns the image with annotated bounding boxes around the detected faces.

## Getting Started

To get started with the Face Detection project, follow these steps:

1. Install the necessary libraries and dependencies:
   - OpenCV: `pip install opencv-python`
   - Mediapipe: `pip install mediapipe`

2. Run the `face_detection_basics.py` script to perform face detection on a video file.

3. Explore the `face_detection_module.py` file to understand the reusable `FaceDetector` class and how it can be integrated into your own projects.

## Usage

- To run the `face_detection_basics.py` script, execute the following command: `python face_detection_basics.py`
- The script will detect faces in the provided video file and display the output with bounding box annotations and confidence scores.
- To utilize the `FaceDetector` class in your own projects, import it from `face_detection_module.py` and create an instance of the class. Use the `findFaces()` method to perform face detection on images.


