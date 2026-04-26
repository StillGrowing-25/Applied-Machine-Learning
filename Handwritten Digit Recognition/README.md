Handwritten Digit Recognition using Neural Networks
Project Overview

This project implements a handwritten digit recognition system using the MNIST dataset. The goal is to classify grayscale images of handwritten digits (0–9) using a neural network model.

Dataset
The project uses the MNIST dataset, which contains:

60,000 training images
10,000 testing images
Image size: 28 × 28 pixels (grayscale)

Each image represents a single digit from 0 to 9.

Technologies Used
Python
TensorFlow / Keras
NumPy
Matplotlib

Data Preprocessing
Normalized pixel values from range (0–255) to (0–1)
Reshaped data for neural network input
Split dataset into training and testing sets

Model Architecture

The neural network consists of:

Flatten layer (converts 2D image into 1D vector)
Dense layer with ReLU activation
Dropout layer for regularization
Output layer with Softmax activation (10 classes)
