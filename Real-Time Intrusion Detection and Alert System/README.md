# Real-Time Intrusion Detection and Alert System

## Overview
This OpenCV project is an intelligent security solution that uses computer vision to detect unknown faces in real-time, send alert messages, and save images of the detected individuals. It leverages OpenCV for face detection, LBPH (Local Binary Patterns Histograms) for face recognition, and integrates with messaging services to provide instant alerts.

## Features
* Real-Time Face Detection: Continuously monitors a video feed for faces.
* Known vs. Unknown Face Recognition: Uses a trained model to differentiate between known and unknown faces.
* Alert Messaging: Sends an alert message when an unknown face is detected.
* Image Saving: Captures and saves the image of any unknown person detected.

## Download pre-trained models:
* Ensure you have the haarcascade_frontalface_default.xml file in the working directory.
* Place your trained face recognizer model as face_recognizer_model.yml in the working directory.

### Notes:
Ensure you replace placeholder email credentials and server settings with actual values.
The script assumes you have a pre-trained LBPH face recognizer model. If not, you will need to train one using your dataset.
