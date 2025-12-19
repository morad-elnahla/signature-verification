# signature-verification

# ✍️ Signature Verification using Siamese Neural Networks

This repository contains a **hands-on academic project** for handwritten signature verification using a **Siamese Neural Network** with **Contrastive Loss**.  
The model learns similarity embeddings to distinguish between **genuine** and **forged** signatures.

---

## 📌 Project Overview

Traditional classification approaches struggle with signature verification due to high intra-class variation.  
This project uses **metric learning** to measure similarity between two signatures instead of classifying them independently.

---

## 🧠 Key Concepts
- Siamese Neural Networks
- Contrastive Loss
- Metric Learning
- Computer Vision
- Deep Learning with PyTorch

---

## 🛠️ Features
- Advanced signature preprocessing (background removal, centering, normalization)
- Pretrained **SigNet** backbone
- Siamese architecture with shared weights
- Contrastive loss + binary classification head
- Model training, evaluation, and inference
- Interactive **Gradio web interface** for real-time verification

---

## 📂 Dataset
The project uses the **Signature Verification Dataset** from Kaggle:

🔗 https://www.kaggle.com/datasets/robinreni/signature-verification-dataset

---

## ⚙️ Preprocessing Steps
- Noise removal using OTSU thresholding
- Signature centering on a fixed canvas
- Image resizing and cropping
- Grayscale normalization

---

## 🏗️ Model Architecture
- SigNet CNN backbone
- Shared-weight Siamese branches
- Feature embedding comparison
- Cosine similarity & projection head
- Binary output for Original vs Forged

---

## 🚀 Training
- Optimizer: Adam
- Loss Functions:
  - Contrastive Loss
  - Binary Cross Entropy
- Learning Rate Scheduling
- Gradient clipping for stability

---

## 📊 Evaluation
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- Cosine similarity analysis

---

## 🌐 Gradio Demo
The project includes a **Gradio interface** that allows users to:
- Upload an original signature
- Upload a suspicious signature
- Get a real-time verification result with confidence score

---

## 🧪 Example Output
- ✔️ ORIGINAL — Confidence: 0.93  
- ⚠️ FORGED — Confidence: 0.87  

---

