# Hand Tracking Project

The Hand Tracking project utilizes OpenCV, Mediapipe, and image processing techniques to track and recognize hand gestures from a webcam feed.

## Description

The Hand Tracking project focuses on real-time hand tracking and gesture recognition using OpenCV and the Mediapipe library. It tracks the user's hand movements and detects various hand landmarks, enabling gesture-based interactions. The project includes functionality for finger counting and overlaying images based on the number of fingers detected.

## Features

- Hand tracking and gesture recognition in real-time
- Detection of hand landmarks and fingertips
- Finger counting based on hand gestures
- Overlaying of images based on finger count

## Files

The project consists of the following files:

- `finger_counting.py`: Tracks and recognizes hand gestures in real-time using the webcam feed. It detects the landmarks of the user's hand and performs finger counting based on the hand gestures. Additionally, it overlays images on the screen based on the number of fingers detected.

- `hand_tracking_module.py`: Contains a reusable class called `handDetector` that encapsulates the functionality of hand tracking using Mediapipe. The class provides methods to find hands in an image and detect hand landmarks and fingertip positions.

## Getting Started

To get started with the Hand Tracking project, follow these steps:

1. Install the necessary libraries and dependencies:
   - OpenCV: `pip install opencv-python`
   - Mediapipe: `pip install mediapipe`

2. Run the `finger_counting.py` script to track hand gestures in real-time using the webcam.

3. Explore the `hand_tracking_module.py` file to understand the reusable `handDetector` class and how it can be integrated into your own projects.

## Usage

- To run the `finger_counting.py` script, execute the following command: `python finger_counting.py`
- The script will start tracking hand gestures from the webcam feed and perform finger counting. It will also overlay images on the screen based on the number of fingers detected.
- To utilize the `handDetector` class in your own projects, import it from `hand_tracking_module.py` and create an instance of the class. Use the `findHands()` method to detect hands in images, and the `findPosition()` method to obtain the positions of hand landmarks and fingertips.
