# Handwritten Digit Recognition Using Neural Networks

## Overview

This project implements a **Neural Network** from scratch to recognize handwritten digits. The model is trained on the **MNIST dataset** and is capable of predicting digits based on user input. The entire process, including the model architecture, training, and saving the model, is done without relying on any deep learning frameworks such as TensorFlow or PyTorch. The model is built using only NumPy for matrix operations and data manipulation.

** Kindly download MNIST handwritten digits (0-9) dataset with training and testing csv files.

## Features

- **Neural Network Model**: Custom-built neural network to recognize handwritten digits.
- **Backend Only**: Model implementation with NumPy without using high-level deep learning frameworks.
- **Training on MNIST**: The network is trained on the MNIST dataset, one of the most well-known datasets for handwritten digit recognition.
- **Model Weights**: The trained model’s weights are saved to a `.npy` file for later use and predictions.

## Technologies Used

- **Python**: Programming language used for the implementation.
- **NumPy**: For matrix operations, forward propagation, and backpropagation.
- **MNIST Dataset**: Standard dataset for training handwritten digit classifiers.

## Getting Started

Follow the steps below to set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pip (Python's package manager)

### Installing Dependencies

1. Clone the repository to your local machine.

   ```bash
   git clone <repository_url>
   cd <repository_directory>
2. ```bash
   pip install -r requirements.txt
4. Requirement.txt should include :
  ```bash
  numpy
  opencv-python
  pillow
