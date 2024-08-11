# Deep Learning Architecture Performance Analysis

## Overview

This repository contains a comprehensive analysis of various deep learning architectures on different datasets. The models evaluated include:

- **LeNet**
- **VGG**
- **ResNet**
- **DenseNet**

The datasets used for the evaluation are:

- **MNIST**
- **Fashion MNIST**
- **CIFAR-10**
- **CIFAR-100**

## Objectives

1. **Evaluate the performance** of LeNet, VGG, ResNet, and DenseNet architectures on the MNIST, Fashion MNIST, CIFAR-10, and CIFAR-100 datasets.
2. **Compare the performance** across different architectures using metrics such as Accuracy, Precision, Recall, F1 Score, and Loss.
3. **Generate confusion matrices** and performance graphs for visualization.
4. **Determine the best-performing model** based on the evaluation metrics.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
  - [MNIST](#mnist)
  - [Fashion MNIST](#fashion-mnist)
  - [CIFAR-10](#cifar-10)
  - [CIFAR-100](#cifar-100)
- [Conclusion](#conclusion)
- [License](#license)

## Requirements

- Python 3.8+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Scikit-learn

You can install the required packages using pip:

pip install tensorflow keras numpy matplotlib scikit-learn

Observations
# Model Performance Metrics

The following tables summarize the performance metrics for DenseNet-169, DenseNet-201, and DenseNet-264 across various datasets.

## DenseNet-169

| Dataset      | Accuracy | Precision | Recall | F1 Score | Loss    |
|--------------|----------|-----------|--------|----------|---------|
| MNIST        | 0.9858   | 0.9858    | 0.9858 | 0.9858   | 0.060246|
| Fashion MNIST| 0.8961   | 0.8961    | 0.8961 | 0.8961   | 0.292071|
| CIFAR-10     | 0.7335   | 0.7335    | 0.7335 | 0.7335   | 0.865075|
| CIFAR-100    | 0.3500   | 0.3500    | 0.3500 | 0.3500   | 2.759743|

## DenseNet-201

| Dataset      | Accuracy | Precision | Recall | F1 Score | Loss    |
|--------------|----------|-----------|--------|----------|---------|
| MNIST        | 0.9920   | 0.9920    | 0.9920 | 0.9920   | 0.032089|
| Fashion MNIST| 0.8958   | 0.8958    | 0.8958 | 0.8958   | 0.317300|
| CIFAR-10     | 0.7098   | 0.7098    | 0.7098 | 0.7098   | 1.048192|
| CIFAR-100    | 0.3578   | 0.3578    | 0.3578 | 0.3578   | 2.660412|

## DenseNet-264

| Dataset      | Accuracy | Precision | Recall | F1 Score | Loss    |
|--------------|----------|-----------|--------|----------|---------|
| MNIST        | 0.9829   | 0.9829    | 0.9829 | 0.9829   | 0.072041|
| Fashion MNIST| 0.8724   | 0.8724    | 0.8724 | 0.8724   | 0.342333|
| CIFAR-10     | 0.7528   | 0.7528    | 0.7528 | 0.7528   | 0.827284|
| CIFAR-100    | 0.3455   | 0.3455    | 0.3455 | 0.3455   | 2.765288|

License
This project is licensed under the MIT License - see the LICENSE file for details.


