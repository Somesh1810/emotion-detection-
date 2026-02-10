#  Emotion Detection App  
### CNN-Based Facial Emotion Recognition using TensorFlow & Streamlit

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)]
[![TensorFlow](https://img.shields.io/badge/Framework-TensorFlow-orange)]
[![Streamlit](https://img.shields.io/badge/Deployment-Streamlit-red)]
[![Deep Learning](https://img.shields.io/badge/Domain-Computer%20Vision-green)]

---

##  Project Overview

The **Emotion Detection App** is a deep learning-based web application that predicts human emotions from facial images using a Convolutional Neural Network (CNN).

Users can upload an image, and the trained CNN model classifies the facial expression into one of seven emotion categories.

The application is deployed using **Streamlit**, making it accessible directly from a browser.

---

##  Live Demo

Try the deployed application here:

**[Open the App](PASTE_YOUR_STREAMLIT_LINK_HERE)**

> No installation required — runs directly in your browser.

---

## Objective

To build and deploy a real-time facial emotion recognition system that:

- Processes uploaded images
- Applies CNN-based deep learning inference
- Predicts emotion categories
- Displays confidence scores

---

## Model Details

- Architecture: Convolutional Neural Network (CNN)
- Input Size: 48x48 grayscale images
- Output Classes (7 Emotions):

  - Angry  
  - Disgust  
  - Fear  
  - Happy  
  - Neutral  
  - Sad  
  - Surprise  

- Model File: `saved_models/emotion_cnn.h5`

---

## Processing Pipeline
Image Upload
↓
Convert to Grayscale
↓
Resize to 48x48
↓
Normalize Pixel Values
↓
Reshape for CNN Input
↓
Model Prediction
↓
Emotion + Confidence Output

---

## Tech Stack

| Layer | Tools Used |
|-------|------------|
| Frontend | Streamlit |
| Backend | Python |
| Deep Learning | TensorFlow / Keras |
| Image Processing | PIL, NumPy |
| Model Type | CNN |

---

## Project Structure

emotion-detection-app/
│
├── streamlit_app.py
├── saved_models/
│ └── emotion_cnn.h5
├── requirements.txt
└── README.md

---

## How to Run Locally

### Clone Repository

``
git clone https://github.com/Somesh1810/emotion-detection-app.git
cd emotion-detection-app ``

## Install Dependencies
pip install -r requirements.txt

## Run Streamlit App
streamlit run streamlit_app.py

## App will open at:
http://localhost:8501

## Key Features

Real-time facial emotion prediction

Confidence score display

Lightweight CNN inference

Clean interactive web interface

Deployable on Streamlit Cloud

## Future Enhancements

Webcam real-time emotion detection

Model accuracy improvement with data augmentation

Deployment on AWS / Azure

REST API version for integration

Emotion analytics dashboard

## Academic Context

Project Type: Deep Learning / Computer Vision
Program: M.Sc. Data Analytics
Institution: CHRIST (Deemed to be University), Bangalore

## Author

Someshwar M
M.Sc. Data Analytics
Aspiring AI / ML Engineer

Mail:someshn@gmail.com
LinkedIn: www.linkedin.com/in/someshwar-m
GitHub: https://github.com/Somesh1810


