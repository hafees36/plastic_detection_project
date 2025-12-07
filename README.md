# Plastic Detection Using MobileNetV2 (Image & Real-Time)

This project uses **Transfer Learning (MobileNetV2)** to detect **plastic vs non-plastic** objects from images and a **live camera feed**.


# Plastic Recognition System

This project implements a simple plastic detection system using deep learning and computer vision techniques. It can detect plastic in images and real-time camera feed using a MobileNetV2-based model.

---

## ✅ Features

- Preprocess raw images to a standardized format
- Train a binary classification model to detect plastic
- Predict plastic presence in a single image
- Real-time plastic detection using webcam

---

## ⚡ Requirements

- Python 3.10
- TensorFlow
- OpenCV
- NumPy

---

It:

- Preprocesses your raw phone images into a clean dataset
- Trains a **binary classifier** (`clean` / `plastic`)
- Saves and reuses a trained model (`plastic_detector.h5`)
- Supports:
  - Testing a **single image**
  - **Real-time** plastic detection using your webcam

---

## 🧩 How It Works

1. **Dataset structure**

You provide raw images in a folder named:

```bash
dataset/
├── clean/
│   ├── img1.jpg
│   ├── img2.jpg
│   └── ...
└── plastic/
    ├── img1.jpg
    ├── img2.jpg
    └── ...







