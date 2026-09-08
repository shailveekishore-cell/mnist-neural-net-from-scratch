# MNIST Digit Recognizer from Scratch
A two-layer neural network built entirely from scratch in Python to classify handwritten digits from the MNIST dataset without using deep learning frameworks like TensorFlow or PyTorch.

## Overview
This project demonstrates the core mathematical mechanics behind deep neural networks by implementing vectorization, forward propagation, activation functions, loss calculation, backpropagation, and gradient descent manually.

## Features & Implementation Details
- **Architecture:** 2-layer fully connected neural network (784 input units $\rightarrow$ 10 hidden units $\rightarrow$ 10 output units).
- **Activation Functions:** 
  - Hidden Layer: ReLU (Rectified Linear Unit)
  - Output Layer: Softmax
- **Optimization:** Gradient Descent with manual derivative calculation for backpropagation.
- **Data Processing:** Normalization and matrix transformation using NumPy and Pandas.

## Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib

## Results
The model learns to classify digits (0–9) directly from 28x28 grayscale pixel arrays, reaching ~85%+ accuracy through iterative gradient updates.
