# 🧠 Simple Neural Network from Scratch (MNIST Digit Classification)

This project implements a simple neural network **from scratch using NumPy**, trained on the MNIST dataset to classify handwritten digits (0–9). No high-level libraries like TensorFlow or PyTorch were used.

## 🚀 Overview
- Pure NumPy-based implementation
- Implements core neural network concepts:
  - Forward propagation
  - Softmax activation
  - One-hot encoding
  - Batch training
  - Model evaluation

## 📊 Results
Achieved over **70% accuracy** on the MNIST test set using:
- 1 hidden layer
- ReLU activation
- Manual vectorized training loop

## 🛠️ Tech Stack
- Python
- NumPy
- Matplotlib (optional for visualization)
- Jupyter Notebook

## 📁 Files
- `Simple Neural Network.ipynb` – Core notebook
- `README.md` – Project description

## 📦 Installation & Usage
```bash
git clone https://github.com/vk-042/simple-nn-mnist.git
cd simple-nn-mnist
pip install numpy
jupyter notebook "Simple Neural Network.ipynb"

## 📌 Output Snapshot

The test accuracy across 10 epochs:

epoch= 0 → accuracy: 79.74%
epoch= 1 → accuracy: 79.81%
epoch= 2 → accuracy: 79.82%
epoch= 3 → accuracy: 79.85%
epoch= 4 → accuracy: 79.88%
epoch= 5 → accuracy: 79.85%
epoch= 6 → accuracy: 79.81%
epoch= 7 → accuracy: 79.84%
epoch= 8 → accuracy: 79.89%
epoch= 9 → accuracy: 79.88%


This model was trained using only **NumPy** with manual forward propagation and weight updates.




