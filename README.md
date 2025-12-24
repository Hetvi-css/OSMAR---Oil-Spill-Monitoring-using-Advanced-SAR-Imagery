# 🛢️ Oil Spill Detection Using Deep Learning on SAR Images

## 📌 Overview
This project focuses on the automatic detection and segmentation of oil spills in marine environments using Synthetic Aperture Radar (SAR) satellite imagery and deep learning techniques. The proposed approach uses a lightweight encoder–decoder architecture with MobileNetV2 as the backbone, enabling efficient and accurate oil spill identification suitable for large-scale and near real-time monitoring.

---

## 🎯 Objectives
- Detect oil spill regions from SAR images  
- Perform pixel-level oil spill segmentation  
- Reduce false positives caused by look-alike ocean phenomena  
- Support rapid environmental monitoring and response  

---

## 🛰️ Dataset
- **Type:** Synthetic Aperture Radar (SAR) images  
- **Image Size:** 512 × 512  
- **Channels:** Single-channel (grayscale)  
- **Annotations:** Pixel-wise binary masks  
- **Preprocessing:** Resizing, normalization, noise handling  

---

## 🧠 Model Architecture
- **Encoder:** MobileNetV2  
- **Decoder:** U-Net style upsampling network  
- **Skip Connections:** For multi-scale feature fusion  
- **Activation Functions:** ReLU6, Sigmoid  
- **Loss Function:** Binary Cross-Entropy / Dice Loss  
- **Optimizer:** Adam  

---

## ⚙️ Methodology
1. Preprocess SAR images  
2. Extract features using MobileNetV2 encoder  
3. Fuse features through skip connections  
4. Segment oil spill regions using decoder layers  
5. Evaluate and visualize predictions  

---

## 📊 Evaluation Metrics
- Intersection over Union (IoU)  
- Dice Coefficient  
- Precision  
- Recall  
- F1-Score  

---

## 🚀 Key Features
- Accurate oil spill segmentation  
- Lightweight and efficient model  
- Robust to SAR noise and ocean clutter  
- Scalable for environmental monitoring applications  

---

## 🌍 Applications
- Marine pollution monitoring  
- Coastal and offshore surveillance  
- Environmental impact assessment  
- Disaster response and management  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / PyTorch  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook  
