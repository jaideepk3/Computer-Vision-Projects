# Computer Vision Projects

This repository contains two computer vision projects developed using OpenCV: Face Detection and Hand Tracking.

## Face Detection

The Face Detection project utilizes OpenCV and the Mediapipe library to detect faces in both videos and images. The Mediapipe Face Detection API is used to locate faces and draw bounding boxes around them. The detected faces are annotated with a confidence score.

### Face Detection Basics

The `face_detection_basics.py` script detects faces in a provided video file using the Mediapipe Face Detection API. Bounding boxes are drawn around the detected faces, and the confidence scores are displayed. The script also calculates and displays the frames per second (FPS).

### Face Detection Module

The `face_detection_module.py` file contains a reusable class called `FaceDetector` that encapsulates the functionality of face detection using Mediapipe. The class provides a `findFaces()` method that takes an image as input and returns the image with annotated bounding boxes around the detected faces.

## Hand Tracking

The Hand Tracking project focuses on detecting hand gestures and counting the number of fingers using a webcam. It utilizes the Mediapipe Hand Tracking API to detect and track hand landmarks. Based on the positions of the landmarks, the number of extended fingers is determined.

### Finger Counting

The `finger_counting.py` script performs finger counting using hand tracking. It detects and tracks hand landmarks using the `HandTrackingModule`. The webcam feed is displayed with an overlay showing the number of extended fingers, along with corresponding images for each finger count.

### Hand Tracking Module

The `HandTrackingModule.py` file contains a reusable class called `handDetector` that encapsulates the functionality of hand detection and tracking using Mediapipe. The class provides methods to find hands in an image and obtain the positions of hand landmarks.

---

Feel free to explore the individual project files for more details and to run the scripts in your local environment.

