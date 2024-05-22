# Image Generation using MNIST Dataset

This project involves training a neural network from scratch to generate fake handwritten images of digits (0-9) using the MNIST dataset. The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits. The data preprocessing steps include normalizing and flattening the images, and converting digit labels into one-hot encoded vectors.

The neural network comprises an input layer, a hidden layer with ReLU activation and dropout for regularization, and an output layer with sigmoid activation. The model is trained using the Adam optimizer over 10,000 epochs with a learning rate of 0.001. Once trained, the model can generate images of digits based on user input, showcasing its ability to create realistic handwritten digit images. The results and generated images demonstrate the effectiveness of the model in learning and replicating the patterns of handwritten digits.
