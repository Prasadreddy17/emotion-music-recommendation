# 🎵 Emotion-Based Music Recommendation System

## 📋 Project Overview
An AI-powered system that detects a user's emotion in real-time using computer vision and recommends personalized music based on the detected emotional state.

## 🎯 Problem Statement
Most music recommendations rely only on listening history. This project goes further — using a webcam to detect how the user feels right now, then recommending music that matches their current mood.

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| MediaPipe | Facial landmark detection |
| TensorFlow / Keras | Emotion classification model |
| NumPy | Data handling (emotion.npy, labels.npy) |

## 🔍 How It Works
1. **Capture** — Webcam captures the user's face in real-time
2. **Detect** — MediaPipe extracts facial landmarks
3. **Classify** — A trained Keras model (model.h5) predicts the emotion
4. **Recommend** — The system maps the detected emotion to a music recommendation

## 📁 Repository Structure

emotion-music-recommendation/

├── src/

│   ├── music.py

│   └── emotion.jpg

└── models/

├── model.h5

├── emotion.npy

└── labels.npy

## 🚀 How to Run This Project
1. Clone this repository: `git clone https://github.com/Prasadreddy17/emotion-music-recommendation`
2. Install required libraries: `pip install tensorflow keras mediapipe numpy opencv-python`
3. Run the script: `python src/music.py`

## 📬 Contact
**Goli Krishna Prasad Reddy**
📧 golikrishnaprasadreddy@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/krishna-prasad-reddy)
