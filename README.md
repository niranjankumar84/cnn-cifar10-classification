# CNN for CIFAR10 Image Classification

This project implements a Convolutional Neural Network (CNN) using PyTorch for image classification on the CIFAR10 dataset.

The objective of this project is to classify RGB images into multiple categories using Deep Learning techniques.

---

# Project Overview

In this project, I built and trained a CNN model from scratch using PyTorch.

The workflow includes:
- Dataset preprocessing
- DataLoader implementation
- CNN architecture design
- Model training
- Validation loss tracking
- Accuracy evaluation
- Overfitting analysis

---

# Dataset Used

CIFAR10 Dataset

The dataset contains 10 image classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

Image Size:
32 × 32 RGB images

---

# Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- NumPy

---

# Concepts Covered

- Convolutional Neural Networks (CNN)
- Conv2D layers
- ReLU activation
- MaxPooling
- Feature maps
- Forward propagation
- Backpropagation
- CrossEntropyLoss
- Adam optimizer
- Training and validation loss
- Accuracy calculation
- Overfitting detection

---

# CNN Architecture

Conv2D → ReLU → MaxPooling
↓
Conv2D → ReLU → MaxPooling
↓
Conv2D → ReLU → MaxPooling
↓
Flatten
↓
Fully Connected Layer
↓
Output Layer

---

# Project Structure

```text
cnn-cifar10-classification/
│
├── CNN_for_CIFAR10.ipynb
├── data_batch_1
├── data_batch_2
├── data_batch_3
├── data_batch_4
├── test_batch
├── batches.meta
├── README.md
└── requirements.txt
