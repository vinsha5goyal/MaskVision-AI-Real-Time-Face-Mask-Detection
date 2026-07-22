# MaskVision-AI-Real-Time-Face-Mask-Detection

# 🛡️ MaskVision-AI: Real-Time Face Mask Detection

## 📌 Overview

MaskVision-AI is an end-to-end **Deep Learning** and **Computer Vision** project that detects whether a person is wearing a face mask in real time. The system combines **Transfer Learning**, **OpenCV**, and **Haar Cascade Face Detection** to identify faces from a webcam feed and classify them as **Mask** or **No Mask**.

This project demonstrates the integration of image preprocessing, face detection, deep learning-based classification, and real-time inference into a complete application.

---

## 🚀 Features

- ✅ Real-time face mask detection using webcam
- ✅ Face detection using Haar Cascade Classifier
- ✅ Binary classification (Mask / No Mask)
- ✅ Transfer Learning with VGG16
- ✅ High accuracy (~95–96%)
- ✅ Image preprocessing and normalization
- ✅ Bounding box and prediction label visualization
- ✅ Lightweight and efficient real-time prediction

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Transfer Learning (VGG16)
- Haar Cascade Classifier
- Jupyter Notebook

---

## 🧠 Model Architecture

The project uses **Transfer Learning** with the **VGG16** pre-trained Convolutional Neural Network.

- Pre-trained on ImageNet
- Custom output layer for binary classification
- Sigmoid activation function
- Binary Cross-Entropy Loss
- Adam Optimizer

---

## 🔍 Computer Vision Pipeline

1. Capture video using OpenCV.
2. Detect human faces using Haar Cascade.
3. Crop detected face region.
4. Resize image to **224 × 224** pixels.
5. Normalize pixel values.
6. Predict using the trained VGG16 model.
7. Display **Mask** or **No Mask** with bounding boxes in real time.

---

## 📂 Project Structure

```
MaskVision-AI/
│── MaskVision_AI.ipynb
│── haarcascade_frontalface_default.xml
│── requirements.txt
│── README.md
│── model.h5
│── dataset/
│    ├── with_mask/
│    └── without_mask/
```

---

## 📊 Dataset

The project is trained on a face mask dataset containing images of people with and without masks.

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| Model | VGG16 (Transfer Learning) |
| Classification | Binary |
| Training Accuracy | ~95% |
| Validation Accuracy | ~93–96% |
| Input Image Size | 224 × 224 |

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/vinsha5goyal/MaskVision-AI-Real-Time-Face-Mask-Detection.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
MaskVision_AI.ipynb
```

and run all cells.

---

## 💡 Key Concepts Demonstrated

- Transfer Learning
- Convolutional Neural Networks (CNN)
- Binary Image Classification
- Real-Time Computer Vision
- Face Detection
- Image Preprocessing
- Deep Learning Model Deployment

---

## 📷 Output

The system detects faces in real time and displays:

🟩 **Mask**

🟥 **No Mask**

with bounding boxes around detected faces.

---

## 🎯 Future Improvements

- Deploy as a web application using Flask or Streamlit
- Mobile application integration
- Face Mask Detection using YOLO
- Multi-face tracking
- Support for different mask types

---

## 👩‍💻 Author

**Vinsha Goyal**

GitHub: https://github.com/vinsha5goyal

---

## ⭐ If you found this project useful, consider giving it a Star!
