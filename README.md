# Face Emotion Recognition using Deep Learning

## Overview
This project implements a **Real-Time Face Emotion Recognition System** using **Deep Learning, OpenCV, and Python**.  
The system detects faces from a webcam feed and predicts human emotions using a trained CNN model.

---

## Features
- Real-time face detection using OpenCV Haar Cascade  
- Emotion classification using a trained CNN model  
- Live webcam emotion prediction  
- Image preprocessing (grayscale + resizing)  
- Lightweight and easy to run

---

## Emotion Classes
The model predicts the following emotions:

- Angry  
- Disgust  
- Fear  
- Happy  
- Neutral  
- Sad  
- Surprise  

---

## Project Structure
```
FACE_EMOTION_RECOGNITION/
│
├── images/
│ ├── train/
│ └── test/
│
├── facialemotionmodel.json
├── facialemotionmodel.h5
├── emotiondetector.json
├── emotiondetector.h5
├── realtimedetection.py
├── trainmodel.ipynb
├── requirements.txt
└── README.md
```