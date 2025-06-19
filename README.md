# 🧠 Digit Classifier Web App – ANN + React + Flask

This full-stack machine learning project allows users to draw digits on a React-based canvas, send that input to a Flask API, and receive a prediction using an Artificial Neural Network (ANN) trained on the MNIST dataset.

---

## 🚀 Live Features

- 🎨 Real-time digit drawing canvas
- 📤 Image sent as base64 to Python Flask API
- 🧠 Deep learning ANN model predicts the digit
- 🔁 Instant response displayed on the UI
- 📦 Easy deployment (localhost or Render/Heroku)

---

## ✅ Accuracy

| Metric          | Value       |
|-----------------|-------------|
| Test Accuracy    | **98.0%** ✔️ |

> Model was trained for 10 epochs on the MNIST dataset using ReLU and softmax activations.

---

## 🧠 ANN Model Architecture

| Layer           | Details                          |
|----------------|----------------------------------|
| Input           | 28 × 28 image (flattened)        |
| Hidden Layer    | Dense(128), Activation: ReLU     |
| Output Layer    | Dense(10), Activation: Softmax   |
| Loss Function   | Categorical Crossentropy         |
| Optimizer       | Adam                             |
