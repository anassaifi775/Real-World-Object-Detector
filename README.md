📌 Real-Time Object & Face Detection using OpenCV and YOLO
🔍 Project Overview

This project demonstrates real-time computer vision applications using OpenCV and YOLO (You Only Look Once). It includes implementations for:

Face and eye detection using Haar Cascade classifiers

Object detection using YOLOv8

Image-based detection for easy experimentation

Webcam-based real-time detection for local environments

The project is designed to help understand how object detection models work in real-world scenarios using Python.

🛠 Technologies Used

Python

OpenCV

YOLOv8 (Ultralytics)

NumPy

🚀 Features

Detects faces and eyes in static images

Performs real-time object detection using YOLOv8

Draws bounding boxes and class labels on detected objects

Easy-to-modify code for experimenting with different models

Beginner-friendly and well-structured

⚠️ Important Note on Camera Access

Webcam / camera-based detection works only on local environments such as:

VS Code

PyCharm

Local Jupyter Notebook

Due to hardware access limitations, Google Colab does not support direct webcam access using OpenCV (cv2.VideoCapture(0)).
For Colab, the project supports image or video-based detection only.

📂 How to Run (Local Machine)
pip install opencv-python ultralytics numpy

python object_detection.py


Make sure:

Your webcam is connected

You are running the project locally (not on Google Colab)

📌 Use Cases

Computer Vision learning projects

AI/ML portfolio projects

Real-time object detection demos

Beginner OpenCV practice

📎 Future Improvements

FPS counter for performance analysis

Video file detection support

Model optimization for faster inference

Face recognition integration

👨‍💻 Author

Mohd Anas
Aspiring Data Analyst | Computer Vision & AI Enthusiast
