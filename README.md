# 🧠 Gender and Age Detection with OpenCV

![License](https://img.shields.io/github/license/smahesh29/Gender-and-Age-Detection)
![Python](https://img.shields.io/badge/python-3.6%2B-blue)

## 🎯 Objective

A Python-based tool that detects **gender and age** from an image or webcam feed using deep learning models.  
It uses OpenCV’s deep neural network (DNN) module along with pretrained `.caffemodel` and `.pb` files.

---

## 🧰 Tech Stack

- Python 3.6+
- OpenCV (with `cv2.dnn`)
- Pretrained Caffe models for age & gender
- TensorFlow face detection model

---

## 📂 Project Structure

Gender-and-Age-Detection/
│
├── detect.py # Main script
├── age_deploy.prototxt # Age model architecture
├── age_net.caffemodel # Age model weights
├── gender_deploy.prototxt # Gender model architecture
├── gender_net.caffemodel # Gender model weights
├── opencv_face_detector.pbtxt # Face detector config
├── opencv_face_detector_uint8.pb # Face detector model
├── girl1.jpg / man1.jpg # Sample test images
└── README.md

## 📦 Requirements

Install the required libraries:

```bash
pip install opencv-python argparse


### ✅ Next Steps (Optional):
- Add **requirements.txt** or a `virtualenv`
- Include **more sample images**
- Build a **Tkinter or Streamlit GUI**

