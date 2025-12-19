# 📌 Real-Time Object & Face Detection using OpenCV and YOLO

## 🔍 Project Overview
This project demonstrates real-world computer vision applications using both traditional image processing techniques and deep learning-based object detection. It combines OpenCV Haar Cascade classifiers for face and eye detection with YOLOv8 for general object detection.

The project is designed for learning, experimentation, and portfolio demonstration of computer vision concepts using Python.

---

## 🛠 Technologies Used
- Python
- OpenCV
- YOLOv8 (Ultralytics)
- NumPy

---

## 🚀 Features
- Face detection using Haar Cascade classifiers
- Eye detection within detected faces
- Object detection using YOLOv8 (pretrained on COCO dataset)
- Bounding boxes and class labels on detected objects
- Image-based detection
- Real-time webcam detection (local execution)
- Clean and modular code structure

---

## ⚠️ Camera & Environment Limitations
Real-time webcam detection **works only in local environments**, such as:
- VS Code
- PyCharm
- Local Jupyter Notebook

Google Colab does **not** support direct webcam access using OpenCV (`cv2.VideoCapture(0)`).

In Google Colab:
- Image-based detection is supported
- Video file–based detection is supported
- Webcam-based real-time detection is **not supported**

---

## 📂 Project Structure
```
├── object_detection.py
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── yolov8n.pt
├── sample_images/
└── README.md
```

---

## ▶️ How to Run the Project (Local Machine)

### 1️⃣ Install Dependencies
```bash
pip install opencv-python ultralytics numpy
```

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 3️⃣ Run the Script
```bash
python object_detection.py
```

Make sure:
- Your webcam is connected
- You are running the project locally (not on Google Colab)

---

## 📌 Use Cases
- Learning computer vision fundamentals
- Face and eye detection systems
- Real-time object detection demos
- AI / ML portfolio projects
- Surveillance and monitoring prototypes
- OpenCV and YOLO practice for beginners

---

## 🔮 Future Improvements
- Add FPS (frames per second) counter
- Support video file input
- Improve detection accuracy and performance
- Add face recognition functionality
- Object tracking across frames
- Deploy as a web or desktop application
- Optimize models for edge devices

---

## 📎 Dataset & Models
- YOLOv8 pretrained on the COCO dataset
- Haar Cascade XML files provided by OpenCV

---

## 👨‍💻 Author
**Mohd Anas**  
Aspiring Data Analyst | Computer Vision & AI Enthusiast

---

## ⭐ Acknowledgements
- OpenCV community
- Ultralytics YOLO
- COCO Dataset contributors

---

⭐ If you find this project helpful, feel free to star the repository!
