# CIFAR-10 Image Classification using ANN and CNN

## Overview

This project compares Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) on the CIFAR-10 image classification dataset.

The objective is to understand why CNNs perform better than traditional ANN architectures for image-related tasks.

---

## Dataset

CIFAR-10 Dataset

- 60,000 color images
- 10 classes
- 50,000 training images
- 10,000 testing images

Classes:

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

---

## Models Implemented

### ANN Model

- Dense(1024)
- Dense(512)
- Dense(256)
- Dense(128)
- Dropout Layers
- ReLU Activation
- Softmax Output

### CNN Model

- Conv2D(32)
- Conv2D(64)
- Conv2D(128)
- Batch Normalization
- Max Pooling
- Dropout
- Dense Layers

---

## Additional Improvements

Implemented the following tasks:

- Increased ANN layers
- Changed CNN filters to 32 → 64 → 128
- Increased epochs from 10 to 20
- Added EarlyStopping
- Added Data Augmentation
  - Random Flip
  - Random Rotation
  - Random Zoom

---

## Results

| Model | Test Accuracy |
|---------|---------|
| ANN | 44.25% |
| CNN | 73.13% |

---

## Key Learnings

- ANN treats images as flat vectors.
- CNN preserves spatial information.
- CNN significantly outperforms ANN for image classification.
- Data augmentation improves model generalization.
- EarlyStopping helps prevent overfitting.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

---

## Author

Aayush Kumar
