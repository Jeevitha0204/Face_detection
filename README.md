# Real-Time Face Detection using OpenCV

This project implements a real-time face detection system using Python and OpenCV. By leveraging Haar Cascade Classifiers, the model identifies human faces in live video streams captured via the system's webcam. It demonstrates core concepts of computer vision including image preprocessing, feature-based detection, and real-time video processing.

# Project Overview

- Detects and highlights human faces using pre-trained Haar Cascade Classifier.
- Uses live video feed (via webcam) and processes each frame in real-time.
- Outputs the detected faces using bounding rectangles.
- Designed for quick demo, experimentation, and future facial recognition enhancements.

# Key Features

- Real-time detection of frontal human faces.
- Utilizes grayscale conversion to speed up detection.
- Built using OpenCV’s Haar feature-based cascade classifiers.
- Cleanly closes with keyboard interrupt (`q`).

# Tech Stack

- **Language:** Python 3.x  
- **Libraries:** OpenCV  
- **Model:** Haar Cascade (`haarcascade_frontalface_default.xml`)  

## 📦 Installation and Setup

```bash
# Clone the repository
git clone https://github.com/Jeevitha0204/Face_detection.git
cd Face_detection

# Install required libraries
pip install opencv-python

How It Works
Loads the Haar Cascade face detection model from OpenCV’s pre-trained XML files
Captures video stream from your default webcam
Converts each frame to grayscale (required by the model)
Detects faces and draws blue rectangles around them
Exits when the user presses the 'q' key
