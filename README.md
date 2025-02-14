# DeepSplit: Neural Network for Mixed Image Separation

## Overview
DeepSplit is a deep learning project that tackles the challenge of separating combined images into their original components. The model takes a mixed image containing overlapped elements from MNIST (handwritten digits) and Fashion-MNIST (clothing items) datasets and reconstructs the original separate images.

## Problem Statement
Given an input image that is a combination of two source images (one from MNIST and one from Fashion-MNIST), the neural network aims to:
- Decompose the mixed input into its original components
- Maintain high fidelity in the reconstructed images
- Minimize the Mean Squared Error (MSE) between predictions and ground truth

## Technical Details

### Dataset
- **MNIST**: Handwritten digits dataset (28x28 grayscale images)
- **Fashion-MNIST**: Clothing items dataset (28x28 grayscale images)
- Images are padded to 32x32 resolution and normalized

### Implementation
- **Framework**: TensorFlow/Keras
- **Input**: Combined grayscale images (32x32)
- **Output**: Two separate reconstructed images
- **Loss Function**: Mean Squared Error (MSE)

### Dependencies
- TensorFlow
- NumPy
- Matplotlib
- Python 3.x

## Results
The model separates mixed images with:
- Low MSE scores
- High visual quality in reconstructed components
- Good performance across different combinations
