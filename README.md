# MNIST Image Classification with Convolutional Neural Network (CNN)

This repository contains code for training a Convolutional Neural Network (CNN) model on the MNIST dataset for image classification. The MNIST dataset consists of grayscale images of handwritten digits (0 to 9) and is commonly used as a benchmark dataset for machine learning experiments.

## Overview

The code provided here demonstrates the process of training a CNN model using the Keras library to classify handwritten digits. It includes the following steps:

1. **Loading the MNIST dataset**: Using Keras's built-in function to load the dataset.
2. **Preprocessing the data**: Normalizing pixel values and one-hot encoding labels.
3. **Defining the CNN model architecture**: Creating a CNN model using Keras's Sequential API.
4. **Compiling the model**: Configuring the model for training with appropriate loss and optimizer.
5. **Training the model**: Training the CNN model on the training data.
6. **Evaluating the model**: Evaluating the trained model on the test set.

## Requirements

- Python 3
- Keras
- NumPy
- Matplotlib (for visualization)

## Installation

1. Clone this repository:


2. Install the required dependencies:


## Usage

Run the main script to train and evaluate the CNN model:

After training and evaluation, the script will provide the following results:

- Training and validation accuracy and loss curves for the CNN model.
- Test accuracy of the CNN model.

These results give insights into the model's performance and its ability to classify handwritten digits accurately.

## Results

You can find the detailed results of the CNN model's performance in the `results/` directory. This directory includes:

- Training and validation accuracy and loss curves plots (`accuracy.png`, `loss.png`).
- Test accuracy result (`test_accuracy.txt`).

## Contributing

Contributions to this project are welcome. If you have any suggestions, enhancements, or bug fixes, please submit a pull request.

