# 🧠 Human Emotion Detection System / Face Recognition System

A real-time **face recognition and emotion detection** system using Machine Learning and webcam input. This application identifies individuals or predicts emotional states based on facial features captured via live video feed.

This project was originally built using the **Olivetti Faces dataset** and an **SVM classifier**, but can be extended to detect emotions by retraining with labeled emotion datasets such as FER-2013 or CK+.

---

## 📸 Overview

This system uses a trained Support Vector Machine (SVM) model to recognize faces or detect emotions from real-time webcam input. The pipeline includes:

- Capturing live video from a webcam.
- Preprocessing each frame (resizing, flattening).
- Classifying identity or emotion using a pre-trained SVM model.
- Displaying predictions directly on the video feed.

The GUI is implemented using **Tkinter**, making it user-friendly and cross-platform.

---

## 🧰 Technologies Used

| Tool/Library       | Purpose                                  |
|--------------------|------------------------------------------|
| Python 3.x         | Programming language                     |
| Scikit-learn       | Dataset loading, SVM classification      |
| NumPy              | Numerical operations                     |
| OpenCV (`cv2`)     | Video capture and image processing       |
| Tkinter            | GUI interface                            |
| PIL / ImageTk      | Handling images in GUI                   |
| joblib             | Model saving/loading                     |
| scikit-image       | Image resizing and transformation        |

---

## 📦 Installation

Make sure you have Python installed, then install the required packages:

```bash
pip install numpy scikit-learn opencv-python pillow joblib scikit-image
