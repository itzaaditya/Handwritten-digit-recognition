# 🧠 Handwritten Digit Classification (0–9) using ANN

This project builds a **Multiclass Image Classifier** using an **Artificial Neural Network (ANN)** to recognize handwritten digits (0 through 9) from grayscale image data. It uses the **ReLU activation** in hidden layers and **softmax** for the output. The model is trained on the **MNIST dataset** using **TensorFlow**, with preprocessing done using **NumPy** and **pandas**.

---

## 📌 Problem Statement

The goal is to classify grayscale images of handwritten digits into 10 categories (0–9). Each image is 28x28 pixels. This is a classic multiclass classification problem used to benchmark machine learning models.

---

## 📁 Project Structure

├── notebooks/
│ └── digit_classifier.ipynb # Jupyter Notebook with training code
├── data/
│ └── mnist.npz # (Optional) Local dataset storage
├── README.md
└── requirements.txt
