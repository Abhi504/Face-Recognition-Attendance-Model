# Face Recognition Attendance Model

This project implements an **automated attendance system** using **face recognition**. It uses a webcam to detect and recognize faces of registered individuals and marks their attendance with a timestamp in a CSV file.

## 📌 Features
- Add new faces to the system easily.
- Real-time face detection and recognition using OpenCV and `face_recognition` library.
- Automatically logs attendance with name and timestamp.
- Stores attendance in a CSV file for easy access.
- Simple and lightweight implementation.

## 🛠️ Requirements
Make sure you have the following installed:

- Python 3.7+  
- OpenCV (`opencv-python`)  
- face_recognition  
- numpy  

Install dependencies with:

```bash
pip install -r requirements.txt

Face-Recognition-Attendance-Model/
│
├── add_faces.py                 # Script to capture and add new faces
├── test.py                      # Main script to run attendance system
├── app.py                       # Optional Flask/Django app (if used for UI)
├── haarcascade_frontalface_default.xml   # Haar cascade for face detection
├── attendance.csv               # Output file with attendance logs
└── README.md                    # Project documentation

