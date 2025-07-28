# 🧠 Neural Network from Scratch with NumPy

> A minimalist implementation of a fully connected feedforward neural network using just Python and NumPy — based on [Victor Zhou’s](https://victorzhou.com/blog/intro-to-neural-networks/) legendary blog series.

Overview

This project builds a simple neural network **from first principles**, without using any ML libraries like TensorFlow or PyTorch. It covers:
- Forward propagation
- Backpropagation
- Loss calculation
- Gradient descent
- Training on toy datasets

The goal is to deeply understand how neural networks work under the hood — and to demystify the black box.

---

Blog Series Reference

This code follows and extends:
- [Part 1: Intro to Neural Networks](https://victorzhou.com/blog/intro-to-neural-networks/)
- [Part 2: Training a Neural Network](https://victorzhou.com/blog/nn-training/)

---

Architecture

- Input layer: accepts features
- Hidden layer(s): fully connected, using sigmoid activation
- Output layer: single neuron for binary classification

You can easily tweak:
- Number of layers
- Neurons per layer
- Activation function (e.g., ReLU)
- Loss function
- Learning rate

---
