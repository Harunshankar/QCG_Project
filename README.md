# Quantum Kernel SVM for Breast Cancer Dataset

This project implements a Quantum Kernel Support Vector Machine (SVM) for classifying the Breast Cancer dataset. The approach uses quantum computing techniques to enhance the kernel method in SVM, potentially improving classification accuracy.

## Overview

The code provided demonstrates the following steps:
- Loading and preprocessing the Breast Cancer dataset.
- Defining a quantum feature map and variational circuit.
- Computing the quantum-enhanced kernel matrix using PennyLane.
- Optimizing the quantum parameters to maximize kernel-target alignment.
- Training a classical SVM on the optimized quantum kernel matrix.
- Visualizing the SVM decision boundary on a 2D plot.
- Evaluating the classifier's accuracy on the test set.

## Prerequisites

Ensure you have the following Python libraries installed:
- `numpy`
- `matplotlib`
- `scikit-learn`
- `joblib`
- `pennylane`
- `scipy`

You can install these libraries using pip:
```sh
pip install numpy matplotlib scikit-learn joblib pennylane scipy
