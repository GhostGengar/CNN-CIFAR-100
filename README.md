# Convolutional Neural Network on CIFAR-100 Dataset
Author: **Tien Dinh**

## Reference
* [Learning Multiple Layers of Features from Tiny Images](https://www.cs.toronto.edu/~kriz/learning-features-2009-TR.pdf), Alex Krizhevsky, 2009.

## Introduction
This model was built using Tensorflow. It was trained on the CIFAR-100 Dataset for 5000 times. I was able to get around 50% of accuracy, which is reasonable since the data has only 500 images per class.

* [The dataset](https://www.cs.toronto.edu/~kriz/cifar.html)

## The Network
The network consists of two convolutional layers followed by its own pooling layer. Then the last pooling layer was connected to a fully connected neural network that consists of 1024 neurons.

## Dependencies
* Tensorflow
* Numpy
* Matplotlib
