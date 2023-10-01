# Image Classification using TensorFlow/Keras

A Simple image classification model trained on the MNIST dataset using TensorFlow/Keras. The MNIST dataset is a collection of grayscale images representing handwritten digits from 0 to 9. The goal of the model is to correctly classify these digits based on the input images.

## Overview

The notebook consists of the following sections:

1. **Data Loading and Preprocessing**: The MNIST dataset is loaded and preprocessed to prepare it for training and evaluation. The images are normalized to have pixel values in the range [0, 1], and the labels are one-hot encoded.

2. **Model Creation**: A basic neural network model with one hidden layer is built for image classification. The model architecture includes a flattening layer, a hidden dense layer with ReLU activation, and an output dense layer with softmax activation for multi-class classification.

3. **Model Training**: The model is trained on the training set for a fixed number of epochs (5 in this notebook) using the Adam optimizer and categorical cross-entropy loss function.

4. **Model Evaluation**: The trained model is evaluated on the test set to calculate its accuracy. The test accuracy is an indicator of how well the model generalizes to unseen data.

5. **User Input and Prediction**: The user can input a path to an image containing a handwritten digit. The program preprocesses the user-provided image and uses the trained model to predict the digit's class. The model's prediction is displayed along with the input image.

## Usage

Follow these steps to use the Jupyter Notebook:

1. Install the required libraries: TensorFlow, Keras, Pillow, matplotlib.

2. Make sure you have the MNIST dataset available or it will be downloaded automatically when using the `mnist.load_data()` function from TensorFlow/Keras.

3. Execute each code cell in the notebook to run the code step by step.

4. To predict a user-provided image, enter the path to the image when prompted. The image should contain a handwritten digit similar to those in the MNIST dataset.

5. The program will preprocess the user-provided image and use the trained model to predict the digit's class. The predicted class will be displayed, along with the input image.

## Note

- The user-provided image should be in grayscale and have a size of 28x28 pixels.
- The model's accuracy depends on the quality and similarity of the user-provided image to the training data.
- The MNIST dataset is widely used for educational purposes and is considered a relatively easy classification task. Advanced models and datasets may require different approaches.
