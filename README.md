# MNIST Digit Classification Model

A Deep Learning model built with TensorFlow and Keras to classify handwritten digits from the classic MNIST dataset.

---

## 📌 Project Overview

This project implements a Multi-Layer Perceptron (MLP) neural network to accurately recognize handwritten digits (0–9). The dataset consists of 60,000 training images and 10,000 test images of $28 \times 28$ pixel grayscale values.

---

## 🛠️ Model Architecture

* **Input Layer:** `Flatten` layer converting $28 \times 28$ images into a 784-dimensional vector.
* **Hidden Layers:** Two `Dense` layers with 128 units each using **ReLU** activation.
* **Output Layer:** `Dense` layer with 10 units using **Softmax** activation for class probabilities.

---

## ⚡ Training & Evaluation

* **Optimizer:** Adam
* **Loss Function:** `sparse_categorical_crossentropy`
* **Metrics:** Accuracy
* **Epochs:** 25 (with a 20% validation split)

---

## 📊 Results

* **Test Accuracy:** **97.73%** on unseen test data.
