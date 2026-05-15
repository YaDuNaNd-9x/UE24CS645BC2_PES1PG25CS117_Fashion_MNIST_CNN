# Fashion MNIST CNN (From Scratch)

## Name: YADUNAND A
## USN: PES1PG25CS117

## Description
This project implements a Convolutional Neural Network (CNN) from scratch using NumPy to classify Fashion MNIST images.

## Dataset
- Fashion MNIST (10 classes of clothing items)
- Loaded using Keras datasets

## Model Architecture
- Conv Layer (1 → 8) + ReLU
- Max Pooling
- Conv Layer (8 → 16) + ReLU
- Max Pooling
- Flatten
- Fully Connected (400 → 128) + ReLU
- Fully Connected (128 → 10)
- Softmax (via loss function)

## Features
- No deep learning frameworks used (only NumPy)
- Manual forward and backward propagation
- Custom loss function (Cross-Entropy)

## How to Run
1. Install dependencies:
