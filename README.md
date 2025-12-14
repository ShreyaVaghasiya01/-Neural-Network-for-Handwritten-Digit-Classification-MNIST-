# 🧠 Neural Network for Handwritten Digit Classification (MNIST)

This project implements a **feed-forward neural network** using **TensorFlow/Keras** to classify handwritten digits (0–9) from the **MNIST dataset**.

The project is completed as part of my **Machine Learning Internship at Codveda Technologies**.

---

## 📌 Project Overview

The objective of this task is to design, train, and evaluate a neural network model for a multi-class classification problem.

### Key Steps:
- Loaded the built-in MNIST dataset
- Normalized image pixel values
- Applied one-hot encoding to labels
- Designed a feed-forward neural network
- Trained the model using backpropagation
- Evaluated model accuracy on test data
- Visualized predictions on sample images

---

## 🧠 Neural Network Architecture

- **Input Layer:** 28 × 28 grayscale images (flattened)
- **Hidden Layer 1:** Dense layer with 128 neurons (ReLU)
- **Hidden Layer 2:** Dense layer with 64 neurons (ReLU)
- **Output Layer:** Dense layer with 10 neurons (Softmax)

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## 📊 Model Performance

- **Training Accuracy:** ~99%
- **Validation Accuracy:** ~97–98%
- **Test Accuracy:** High accuracy on unseen data

The model demonstrates strong generalization with minimal overfitting.

---
📂 **Neural-Network-MNIST/**
├── Neural Networks with TensorFlow.ipynb   # Jupyter Notebook with full implementation  
├── prediction_samples.png      # Sample prediction visualizations
└── README.md                   # Project documentation  




