# FACE_DETECTION
Real-time Face Detection using Python and OpenCV.
# Face Detection using OpenCV

This project implements real-time face detection using OpenCV and Python. It detects human faces in images or live video streams using Haar Cascade Classifiers and draws bounding boxes around the faces.

## Features

- Real-time face detection using webcam
- Face detection in static images
- Simple and clean Python code
- Uses Haar Cascade Classifier (pre-trained by OpenCV)

## Tech Stack

- *Language*: Python  
- *Libraries*: OpenCV, NumPy

## How it Works

1. Load OpenCV’s pre-trained Haar Cascade model.
2. Capture input from webcam or load an image.
3. Convert the image to grayscale for better performance.
4. Detect faces using the classifier.
5. Draw rectangles around detected faces and display the output.

## Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install opencv-python
