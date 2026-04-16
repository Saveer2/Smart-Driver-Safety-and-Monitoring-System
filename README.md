# Smart Driver Safety and Monitoring System

An intelligent driver assistance system that enhances road safety by combining drowsiness detection, lane detection, and traffic sign recognition using computer vision.

## Overview

The Smart Driver Safety and Monitoring System is a hybrid solution designed to reduce road accidents caused by driver fatigue, lane deviation, and missed traffic signs.

It uses:

1. Facial analysis for drowsiness detection
2. Image processing for lane detection
3. Deep learning (CNN) for traffic sign recognition

## Features
1. Drowsiness Detection
Detects eye closure using EAR (Eye Aspect Ratio)
Detects yawning using MAR (Mouth Aspect Ratio)
Provides real-time voice alerts
2. Lane Detection
Detects road lane boundaries using Canny Edge Detection
Uses Hough Transform for line detection
Displays lane overlays on video
3. Traffic Sign Recognition
Classifies traffic signs using CNN model
Supports 43 different traffic sign classes
Displays prediction with confidence score
4. Real-Time GUI
Live camera feed
Visual overlays and alerts
Parameter display (EAR & MAR)

## Technologies Used
Programming Language: Python </br>
Libraries: OpenCV, dlib, NumPy, TensorFlow / Keras, Matplotlib, pyttsx3
