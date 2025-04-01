# FashionMNIST-classification
# Fashion MNIST Classification with TensorFlow

## Overview
This repository contains a neural network model trained on the **Fashion MNIST** dataset using **TensorFlow** and **Keras**. The Fashion MNIST dataset is a collection of grayscale images of 10 different clothing categories, used as a drop-in replacement for the classic MNIST dataset.

## Dataset
- The dataset consists of **70,000 images** (28x28 pixels each).
- **60,000 images** are used for training.
- **10,000 images** are used for testing.
- Classes: `T-shirt/top`, `Trouser`, `Pullover`, `Dress`, `Coat`, `Sandal`, `Shirt`, `Sneaker`, `Bag`, `Ankle boot`.

## Model Architecture
The neural network used in this project consists of:
- Input layer: **Flattened** (28x28 to 784 neurons)
- Hidden layers: **Dense layers** with ReLU activation
- Output layer: **Softmax** activation (10 classes)

## Installation
To run this project, install the required dependencies:
```bash
pip install tensorflow numpy matplotlib
```

## Running the Code
Execute the Jupyter Notebook to train and evaluate the model:
```bash
jupyter notebook fashionmnist.ipynb
```

## Results
- The model achieves around **83.67% accuracy** on the test set (replace with actual result).
- The confusion matrix and accuracy plot are included in the notebook.

## Author
Created by Harsha Priya Putta - Feel free to contribute!

## License
This project is open-source and available under the MIT License.

