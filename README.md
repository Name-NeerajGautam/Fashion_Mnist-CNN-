# Fashion_Mnist-CNN
Project Overview

This project builds a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset.
Fashion MNIST contains 28x28 grayscale images of 10 different clothing items, such as T-shirts, trousers, dresses, shoes, and bags.

The CNN model learns to automatically identify the clothing type from image pixels, achieving high accuracy with minimal preprocessing.

**Dataset**

Name: Fashion MNIST
Source: Keras datasets
Number of classes: 10
Image size: 28x28 pixels, grayscale
Training samples: 60,000
Test samples: 10,000

**Classes**
T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot

**Project Requirements**
Python 3.7+
TensorFlow / Keras
NumPy
Matplotlib (optional, for visualization)


**Model Architecture**

Input Layer: 28x28 grayscale image
Conv2D Layer: 32 filters, 3x3 kernel, ReLU activation
MaxPooling2D Layer: 2x2 pool size
Conv2D Layer: 64 filters, 3x3 kernel, ReLU activation
MaxPooling2D Layer: 2x2 pool size
Flatten Layer
Dense Layer: 128 neurons, ReLU activation
Dropout Layer: 0.5 rate
Output Layer: 10 neurons, softmax activation

**Training**

Loss function: Categorical crossentropy
Optimizer: Adam
Batch size: 64
Epochs: 5–10
Validation split: 0.2

**Results**
Test Accuracy: ~90%
