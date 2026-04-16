# Smart Driver Safety and Monitoring System

An intelligent driver assistance system that enhances road safety by combining drowsiness detection, lane detection, and traffic sign recognition using computer vision.

## Overview

The Smart Driver Safety and Monitoring System is a hybrid solution designed to reduce road accidents caused by driver fatigue, lane deviation, and missed traffic signs.

It uses:

1. Facial analysis for drowsiness detection
2. Image processing for lane detection
3. Deep learning (CNN) for traffic sign recognition

## Features
1. Drowsiness Detection </br>
* Detects eye closure using EAR (Eye Aspect Ratio)</br>
* Detects yawning using MAR (Mouth Aspect Ratio)</br>
* Provides real-time voice alerts</br>
2. Lane Detection</br>
* Detects road lane boundaries using Canny Edge Detection</br>
* Uses Hough Transform for line detection</br>
* Displays lane overlays on video</br>
3. Traffic Sign Recognition</br>
* Classifies traffic signs using CNN model</br>
* Supports 43 different traffic sign classes</br>
* Displays prediction with confidence score</br>
4. Real-Time GUI</br>
* Live camera feed</br>
* Visual overlays and alerts</br>
* Parameter display (EAR & MAR)</br>

## Technologies Used
Programming Language: Python </br>
Libraries: OpenCV, dlib, NumPy, TensorFlow / Keras, Matplotlib, pyttsx3
