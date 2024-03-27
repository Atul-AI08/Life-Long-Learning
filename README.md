# Lifelong Learning for Image Classification

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/)

---

This repository contains Python implementations of Lifelong Learning techniques for image classification tasks using the MNIST and CIFAR-10 datasets. Lifelong Learning encompasses Task Incremental Learning, Class Incremental Learning, and Transfer Learning paradigms.

## Overview

- Framework used : Pytorch
- Dataset : MNIST, CIFAR-10

## Datasets

### MNIST
The MNIST dataset consists of 28x28 grayscale images of handwritten digits (0 to 9). It contains 60,000 training images and 10,000 testing images.

### CIFAR-10
The CIFAR-10 dataset consists of 32x32 color images in 10 classes (e.g., airplane, automobile, bird, cat, etc.). It contains 50,000 training images and 10,000 testing images.

## Architecture

### Neural Network Model
For the MNIST dataset, we've implemented a neural network architecture comprising an input layer, two hidden layers with 400 units each, and an output layer. This architecture is designed to effectively learn patterns from the 28x28 grayscale images of handwritten digits.

### Convolutional Neural Networks
For the CIFAR-10 dataset, we've employed the ResNet-50 architecture followed by fully connected layers. ResNet-50 is a deep convolutional neural network known for its effectiveness in image classification tasks. By leveraging its architecture, we aim to capture intricate features from the 32x32 color images in CIFAR-10 across its ten different classes.

## Lifelong Learning Paradigms

### Task Incremental Learning
Task Incremental Learning involves sequentially learning new tasks while retaining knowledge from previous tasks. In this project, we explore techniques to train models on new tasks without catastrophic forgetting of previously learned tasks.

### Class Incremental Learning
Class Incremental Learning focuses on incrementally learning new classes while maintaining performance on previously seen classes. We investigate methods to adaptively update the model to accommodate new classes without significantly affecting performance on existing classes.

### Transfer Learning
Transfer Learning leverages knowledge learned from one task to improve learning or performance in another related task. We explore strategies to transfer knowledge from pre-trained models on source tasks to enhance performance on target tasks.
