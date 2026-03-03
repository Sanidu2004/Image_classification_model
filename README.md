# Image Classification with CIFAR-10

A simple image classification project using TensorFlow/Keras to classify images from the CIFAR-10 dataset.

## About

This project compares two neural network approaches:

- **ANN (Artificial Neural Network)** - Basic fully connected network
- **CNN (Convolutional Neural Network)** - Advanced network with convolutional layers

## Dataset

CIFAR-10 contains 60,000 images (32x32 pixels) in 10 classes:

- Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, Truck

## Installation

```bash
pip install tensorflow numpy matplotlib scikit-learn seaborn
```

## Usage

Open and run the Jupyter notebook:

```bash
jupyter notebook ImageClassification.ipynb
```

## Models

### ANN Model

- 3 Dense layers (3000 → 1000 → 10 units)
- Optimizer: SGD
- Epochs: 5

### CNN Model

- 2 Conv2D layers (32 and 64 filters)
- 2 MaxPooling layers
- Dense layers (64 → 10 units)
- Optimizer: Adam
- Epochs: 10

## Results

The CNN model performs better than ANN for image classification tasks due to its ability to learn spatial features.

## Files

- `ImageClassification.ipynb` - Main notebook with all code
- `README.md` - This file
