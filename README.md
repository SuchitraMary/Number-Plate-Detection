# 🚗 Number Plate Detection Using OpenCV
## 📊 Project Overview

This project implements a real-time vehicle number plate detection system using the OpenCV library and a Haar Cascade classifier.

The system captures live video from a webcam, detects vehicle number plates, highlights them with bounding boxes, and allows saving the detected plate images.

---
## 🎯 Project Objective

- Detect vehicle number plates in real-time

- Draw bounding boxes around detected plates

- Extract Region of Interest (ROI)

- Save detected plate images

- Build a foundational Computer Vision application

---
## 💼 Applications

- Number plate detection systems are widely used in:

- Smart parking systems

- Automated toll collection

- Traffic monitoring

- Security and surveillance

- Vehicle access control systems

---
## 🛠️ Technologies Used

- Python

- OpenCV

- Haar Cascade Classifier

- Computer Vision

---
## 📂 Project Structure

number_plate_detection/

│

├── number_plate_detection.py

├── haarcascade_russian_plate_number.xml

├── Saved_Images/

├── assets/

└── README.md

---
## 🔎 Project Workflow

1️⃣ Capture live video using webcam

2️⃣ Convert frame to grayscale

3️⃣ Detect number plates using Haar Cascade

4️⃣ Filter detections based on minimum area

5️⃣ Draw bounding box around detected plate

6️⃣ Extract and display ROI

7️⃣ Press 's' to save detected image

---
## ▶️ How to Run the Project

1️⃣ Install Requirements

pip install opencv-python

2️⃣ Ensure Haar Cascade File is Present

Make sure the file 'haarcascade_russian_plate_number.xml' is inside the project folder.

3️⃣ Run the Script

python number_plate_detection.py

---
## ⌨️ Controls

| Key | Action |
|-----|--------|
| s   | Save detected number plate image |
| q   | Quit program (if implemented) |

---
## 📸 Output

### 🔹 Detection Output
- Displays live camera feed.
- Draws a rectangle around detected number plate.
- Shows "Number Plate" label above the rectangle.

### 🔹 ROI Output
- Displays cropped image of the detected number plate.
- Opens in a separate window.
- Can be saved by pressing 's' key.

---
## 🚀 Future Improvements

- Integrate OCR using Tesseract to extract plate numbers

- Improve detection accuracy using Deep Learning models

- Store detected plate numbers in a database

- Deploy as a web application
  
---
## 📌 Conclusion

This project demonstrates how traditional computer vision techniques such as Haar Cascade can be used for real-time object detection.

It serves as a foundational step toward building advanced Automatic Number Plate Recognition (ANPR) systems.

---
## 👩‍💻 Author

Suchitra Mary

MSc Data Science

Aspiring Machine Learning & Computer Vision Engineer

---
