+++
title = 'Real-Time Sign Language Detector Using OpenCV & MediaPipe'
date = 2025-06-18T00:22:53+01:00
draft = false
+++

This was my first team project as a Computer Science student. We built a real-time sign language detection system that uses a webcam to capture hand gestures and classify them into basic sign-language categories.

## Tech Stack we used

- Python
- OpenCV
- MediaPipe
- scikit-learn

The project was structured into four seperate python programs:

1. `collect_imgs.py` – Capture 100 images per gesture class
2. `create_dataset.py` – Label and organize the dataset
3. `train_classifier.py` – Extract features and train a simple ML model
4. `inference_classifier.py` – Perform live classification via webcam 

The system can classify around 10 different gestures in real time and gave me an amazing introduction into both machine learning and collaborating as a team. It can be found [here](https://github.com/Vvorx/SignLanguageDetector)

