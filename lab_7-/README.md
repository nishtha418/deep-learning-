# Deep Learning Lab 7 — From Numbers to Vision

This assignment focuses on understanding how neural network design choices affect learning. All models were implemented **from scratch using NumPy**, without using any deep learning libraries such as TensorFlow, PyTorch, or Scikit-learn.

## Dataset

A synthetic dataset of **3000 samples** was generated using two input features.
The data was split into:

* 70% Training
* 15% Validation
* 15% Test

## Models Implemented

Three fully connected neural network architectures were built:

* 2-layer network
* 5-layer network
* 10-layer network

Each hidden layer contains at least 4 neurons and the output layer uses a sigmoid activation.

## Experiments

The following comparisons were performed:

* **Activation functions:** ReLU vs Sigmoid
* **Optimizers:** SGD vs Momentum
* **Network depth:** 2, 5, and 10 layers

In total, **12 models** were trained and evaluated.

## Evaluation

For each experiment, the following were monitored:

* Training Loss vs Epoch
* Validation Loss vs Epoch
* Training Accuracy vs Epoch
* Validation Accuracy vs Epoch

After selecting the best model using validation results, the final performance was reported on the **test set**.

## Key Goal

The objective of this lab was to understand how **network depth, activation functions, and optimization methods influence learning behavior in neural networks**.
