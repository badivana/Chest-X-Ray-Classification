![Python](https://img.shields.io/badge/Python-3.x-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
# 🩺 Chest X-Ray Pneumonia Detection using Deep Learning

A deep learning project that classifies chest X-ray images into **Normal** and **Pneumonia** using **PyTorch** and **Transfer Learning**.

## 📑 Table of Contents

- Project Overview
- Features
- Dataset
- Technologies Used
- Model Architecture
- Results
- Installation
- Project Structure
- Future Improvements
- Author
- License

## 📌 Project Overview

Pneumonia is a serious lung infection that can be detected through chest X-ray images. Manual diagnosis can be time-consuming and depends on the expertise of radiologists.

This project uses a deep learning model based on **PyTorch** and **Transfer Learning** to automatically classify chest X-ray images into:

- Normal
- Pneumonia

The objective is to demonstrate how convolutional neural networks can assist in medical image classification.

## ✨ Features

- Data preprocessing and augmentation
- Transfer Learning using ResNet50
- Binary classification (Normal vs Pneumonia)
- Model training and validation
- Performance evaluation
- Prediction on new chest X-ray images

## 📂 Dataset

The dataset consists of chest X-ray images categorized into:

- Normal
- Pneumonia

### Dataset Source

Google Drive:

https://drive.google.com/file/d/1d6G2RkXVNnMBJTO-QWCx6QZ2bMElMqgu/view

After downloading, extract the dataset into the `dataset/` folder.

## 🛠 Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Pillow
- Scikit-learn

## 🧠 Model Architecture

The model follows the following pipeline:

Chest X-ray Image
        ↓
Image Preprocessing
        ↓
Resize (224 × 224)
        ↓
Normalization
        ↓
ResNet50 (Pretrained)
        ↓
Fully Connected Layer
        ↓
Prediction

## 📈 Results

The trained model successfully classifies chest X-ray images into Normal and Pneumonia categories.

Evaluation metrics and visualizations will be added in future updates.

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/badivana/Chest-X-Ray-Classification.git

cd Chest-X-Ray-Classification
```

Install dependencies

```bash
pip install -r requirements.txt
```

## 📁 Project Structure

Chest-X-Ray-Classification/

├── README.md

├── requirements.txt

├── LICENSE

├── train_model.ipynb

├── best_model.pth

├── dataset/

├── images/

└── src/

## 🚀 Future Improvements

- Deploy using Streamlit
- Multi-class disease classification
- Vision Transformer implementation
- Explainable AI using Grad-CAM
- Docker support

## 👨‍💻 Author

**Prajwal B T**

Information Science & Engineering

NMAM Institute of Technology

GitHub: https://github.com/badivana

## 📄 License

This project is licensed under the MIT License.


