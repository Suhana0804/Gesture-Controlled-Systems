# Gesture-Controlled Systems

This repository contains Computer Vision and Gesture Recognition projects developed using Python, OpenCV, and MediaPipe.

The projects demonstrate how webcam input, image processing, and hand/face tracking can be used to build real-time interactive systems and gesture-controlled applications.

The repository includes:
- Face and Eye Detection
- Hand Gesture Recognition
- Virtual Mouse Control

# Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- PyAutoGUI


# Face and Eye Detection

This project uses OpenCV Haar Cascade classifiers to detect faces and eyes in real-time using a webcam.

The system:
- Detects faces from webcam input
- Detects eyes inside the detected face region
- Draws bounding boxes around detected objects
- Displays live video output

## Features

- Real-time face detection
- Eye detection
- Webcam processing
- Haar Cascade implementation
- Bounding box visualization

## Concepts Used

- Computer Vision
- Object Detection
- Image Processing
- Region of Interest (ROI)
- Haar Cascade Classifiers
  

# Hand Gesture Recognition

This project uses MediaPipe and OpenCV to detect and recognize hand gestures in real-time.

The system tracks hand landmarks and identifies gestures based on finger positions.

Recognized gestures include:
- Victory sign
- Thumbs up
- Open palm
- Closed palm
- OK gesture
- Three fingers
- Swag gesture

## Features

- Real-time hand tracking
- Finger landmark detection
- Gesture recognition logic
- Webcam interaction
- Landmark visualization

## Concepts Used

- Hand Tracking
- Landmark Detection
- Gesture Classification
- Real-time Video Processing
- Human-Computer Interaction


# Virtual Mouse Control

This project converts hand gestures into mouse controls using MediaPipe, OpenCV, and PyAutoGUI.

The webcam tracks hand movements and maps finger positions to screen coordinates for cursor control.

The system includes:
- Cursor movement using hand gestures
- Left click gesture
- Right click gesture
- Smooth cursor movement
- Real-time interaction

## Features

- Gesture-controlled mouse movement
- Cursor smoothing
- Gesture-based clicking
- Coordinate mapping
- Real-time automation system

## Concepts Used

- Gesture Controlled Systems
- Automation
- Coordinate Mapping
- Cursor Control
- Human-Computer Interaction
- Computer Vision


# How to Run

## Install Required Libraries

pip install opencv-python 
pip install mediapipe 
pip install pyautogui 
pip install numpy

## Run any file using:
python filename.py

## Press:

ESC to close OpenCV windows

Q where specified in the program

# Project Learning Outcomes

Through these projects, the following concepts were explored:

Real-time Computer Vision
Webcam Frame Processing
Face and Hand Detection
Gesture Recognition Systems
OpenCV Image Processing
MediaPipe Landmark Tracking
Mouse Automation using Python
Human-Computer Interaction Systems

These projects also helped in understanding:

Real-time webcam data handling
Screen coordinate mapping
Landmark-based gesture analysis
Interactive system development
Practical applications of Computer Vision

# Future Improvements

Possible future upgrades include:

Gesture-based volume control
Multi-hand gesture support
AI-based gesture classification
Improved gesture accuracy
Gesture-controlled applications and games
Face recognition with identity tracking
Gesture-based keyboard shortcuts
Virtual drawing and presentation controls
