# Image Generation using MNIST Dataset

This project involves training a neural network model from scratch on the MNIST dataset to generate fake handwritten images of digits from 0-9.

## Table of Contents
1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Architecture](#model-architecture)
5. [Training the Model](#training-the-model)
6. [Generating Images](#generating-images)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

## Installation

To run this project, you'll need to have Python installed along with the following libraries:

```bash
pip install numpy matplotlib tensorflow

## Dataset
We use the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits from 0 to 9.
```bash
from keras.datasets import mnist

(train_images, train_labels), (test_images, test_labels) = mnist.load_data()
print(train_images.shape)  # (60000, 28, 28)
print(train_labels.shape)  # (60000,)
print(test_images.shape)   # (10000, 28, 28)
print(test_labels.shape)   # (10000,)

