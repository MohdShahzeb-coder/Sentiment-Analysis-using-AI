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


---

## Technologies Used
- Python  
- OpenCV  
- TensorFlow / Keras  
- NumPy  

---

## Installation

1. Clone the repository:
  ```
  git clone https://github.com/MohdShahzeb-coder/Sentiment-Analysis-using-AI.git
  ```
2. Navigate to project folder:
   ```
   cd face-emotion-recognition
   ```
3. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

4.Run the real-time detection script:
```
python realtimedetection.py
```

## Dataset
```
images/train
images/test
```
