# Waste Classification Using CNN

A deep learning project for **automatic waste classification using Convolutional Neural Networks (CNNs)**.

This project explores and compares three popular pretrained CNN architectures for image-based waste classification:

- **ResNet50**
- **MobileNetV2**
- **DenseNet201**

The models are implemented and evaluated using Jupyter Notebooks.

---

## 📌 Project Overview

Proper waste classification is an important step toward effective waste management and recycling.

This project applies **transfer learning with pretrained CNN architectures** to classify waste images into their respective categories.

The main goal is to investigate how different CNN architectures perform on the same waste classification task.

---

## 🧠 Models Used

### 1. ResNet50

**ResNet50** is a 50-layer deep convolutional neural network that uses residual connections to make training deep networks more effective.

Notebook:

`ResNet50.ipynb`

---

### 2. MobileNetV2

**MobileNetV2** is a lightweight CNN architecture designed for efficient image processing with relatively low computational requirements.

Notebook:

`MobileNetV2.ipynb`

---

### 3. DenseNet201

**DenseNet201** is a deep CNN architecture where each layer receives feature maps from previous layers, allowing efficient feature reuse.

Notebook:

`DenseNet201.ipynb`

---

## 📂 Repository Structure

```text
waste-classification-cnn/
│
├── DenseNet201.ipynb
├── MobileNetV2.ipynb
├── ResNet50.ipynb
└── README.md
