# 🧠 Handwritten Digit Classification with Differential Evolution & Neural Networks

This project demonstrates how to train a simple neural network to classify handwritten digits using two different optimization techniques:

- ✅ **Gradient Descent**
- 🧬 **Differential Evolution** (a nature-inspired algorithm)

It uses the classic **MNIST** dataset and tests both optimizers on recognizing handwritten digits from external image samples.

---

## 📦 What's Inside

- A simple fully connected neural network built from scratch using **NumPy**
- Two training approaches:
  - `Gradient Descent`: Standard backpropagation-based training
  - `Differential Evolution`: Population-based metaheuristic optimization
- A test function to predict digits from custom images in a local folder

---

## 🔍 Why Differential Evolution?

While gradient-based methods are fast and common, they can:
- Get stuck in local minima
- Be sensitive to initialization

Differential Evolution offers a global search perspective, which can sometimes produce better accuracy or escape poor minima.

---

## 🧪 Try It Yourself

1. Add your own 28x28 grayscale digit images in a folder (e.g., `handwritten_samples/`)
2. Run the provided `predict()` function to see how both models perform
3. Compare predictions from **Gradient Descent** and **Differential Evolution**

---

## 🛠 Tech Stack

- Python
- NumPy
- PIL (Pillow)
- Matplotlib (for visualization)

---

## 📁 File Overview

- `DE_MNIST.ipynb`: Full code notebook (training, DE logic, prediction)
- `handwritten_samples/`: Folder for test images (you can add your own)

---
