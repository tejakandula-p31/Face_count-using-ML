# 👤 Face Count using ML

A simple machine learning-based application that detects and counts the number of human faces in a given image using Python, OpenCV, and Haar Cascade classifiers.

## 📸 Project Overview

This project demonstrates how to:
- Use OpenCV's Haar Cascade face detection algorithm.
- Build a simple face detection pipeline in Python.
- Automatically count the number of human faces in images.
- Display the result with bounding boxes and face count using GUI.

---

## 🚀 Features

✅ Detect faces in a given image  
✅ Count total number of faces  
✅ Display the image with rectangles around each detected face  
✅ GUI-based interface using `tkinter`  
✅ Works with static images via file upload

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - OpenCV (`cv2`)  
  - NumPy  
  - tkinter (for GUI)  
- **ML Model:** Haar Cascade Classifier (pre-trained)

---

## 🧑‍💻 How it Works

1. Load the image from the system using file dialog.
2. Convert the image to grayscale (as required by Haar Classifier).
3. Load the pre-trained Haar Cascade for frontal face detection.
4. Detect faces using `detectMultiScale()`.
5. Draw rectangles around detected faces.
6. Show the image and display the number of faces.

---

## ✅ Applications

1.Classroom or crowd analysis
2.Surveillance systems
3.People counting in public places
4.Attendance automation (extension idea)

---

## 💡 Future Scope

1. Load the image from the system using file dialog.
2. Convert the image to grayscale (as required by Haar Classifier).
3. Load the pre-trained Haar Cascade for frontal face detection.
4. Detect faces using `detectMultiScale()`.
5. Draw rectangles around detected faces.
6. Show the image and display the number of faces.


