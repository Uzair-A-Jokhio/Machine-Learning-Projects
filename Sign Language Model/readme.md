# Convolutional Neural Network (CNN) Model for Sign Language Recognition

![my_image.png](images/amer_sign2.png)

## Overview

This repository contains a Convolutional Neural Network (CNN) model for recognizing sign language gestures corresponding to the American Sign Language (ASL) alphabet from A to Z. The model has been trained on a dataset of sign language images and can be used for real-time prediction of sign language gestures

## Usage

### Prerequisites

Before using this model, make sure you have the following prerequisites installed:

- Python (3.6 or higher)
- TensorFlow (2.x)
- NumPy
- Matplotlib (for visualization)

## Model Architecture

Our CNN model is built using TensorFlow and follows the following architecture:

    Input Layer (28x28 grayscale images)
    Convolutional Layers with ReLU activation
    MaxPooling Layers
    Dropout
    Flatten Layer
    Fully Connected (Dense) Layers
    Output Layer (26 classes, one for each letter from A to Z)

