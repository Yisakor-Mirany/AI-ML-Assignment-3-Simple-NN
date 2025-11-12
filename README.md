# 🧠 AI-ML-Assignment-3-Simple-NN

**Author:** Yisakor Mirany  
**Framework:** TensorFlow / Keras  

## 📌 Project Overview
This project implements a simple **Feedforward Neural Network (FNN)** to classify handwritten digits (0–9) using the **MNIST dataset**.  
The model learns visual features of digits through fully connected layers and demonstrates the basic workflow of deep learning:  
data preprocessing, training, evaluation, and prediction.

---

## 🧱 Model Architecture
- **Input Layer:** 784 neurons (flattened 28×28 images)  
- **Hidden Layer 1:** 128 neurons, ReLU activation  
- **Hidden Layer 2:** 64 neurons, ReLU activation  
- **Output Layer:** 10 neurons, Softmax activation  

---

## ⚙️ Training Configuration
- **Loss Function:** Categorical Cross-Entropy  
- **Optimizer:** Adam  
- **Metrics:** Accuracy  
- **Epochs:** 10  
- **Batch Size:** 128  

---

## 📊 Results
| Metric | Value |
|--------|--------|
| Test Accuracy | ~97% |
| Training Time | ≈ 2 minutes on CPU |

---

## 🧪 Demo
- The notebook includes a random test image prediction demo.  
- Displays both **true label** and **model prediction**.  

---

## 🗂️ Files
- `MNIST_FNN.ipynb` → Complete Jupyter Notebook with code, explanations, and results  
- `README.md` → Project overview and setup instructions  

---
