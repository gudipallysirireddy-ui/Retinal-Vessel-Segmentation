# Retinal Blood Vessel Segmentation from Fundus Images
## 📌 Overview
This project focuses on automatic segmentation of retinal blood vessels from fundus images using Deep Learning techniques. 
The model helps in early detection of diseases such as Diabetic Retinopathy, Hypertension, and Glaucoma. 
A deep convolutional neural network (U-Net / Hybrid U-Net / ResNet / EfficientNet) is used for accurate vessel extraction.
## 🎯 Problem Statement
Manual segmentation of retinal blood vessels is time-consuming and error-prone. 
The goal of this project is to develop an automated deep learning-based system 
to accurately segment major and thin retinal vessels from fundus images.
## 📂 Dataset
The model is trained and evaluated on the DRIVE dataset.
- Total images: 40
- Resolution: 565 × 584
- Ground truth vessel masks provided
## ⚙️ Methodology
1. Image Preprocessing (Resize, Normalization)
2. Data Augmentation
3. Model Architecture (U-Net / Hybrid U-Net)
4. Loss Function: Dice Loss / BCE Loss
5. Evaluation Metrics: Accuracy, Dice Score, IoU
## 🧠 Model Architecture
- Encoder: Pretrained ResNet18 / EfficientNet-B0
- Decoder: U-Net style upsampling blocks
- Skip connections for fine vessel segmentation
## 📊 Results

| Metric | Value |
|--------|--------|
| Accuracy | 95% |
| Dice Score | 0.87 |
| IoU | 0.81 |
## 📦 Requirements
- Python 3.8+
- PyTorch
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
