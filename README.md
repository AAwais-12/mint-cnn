
# mint-cnn

Convolutional Neural Network for Handwritten Digit Classification on the MNIST Dataset using Keras.

---

## Project Overview

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0-9) using the popular MNIST dataset. The CNN is built with TensorFlow Keras and includes several convolutional, batch normalization, ReLU activation, and pooling layers.

---

## Objectives and Goals

- Build and train a CNN to recognize handwritten digits.
- Achieve high accuracy on the test dataset.
- Understand data preprocessing, CNN architecture, training, and evaluation.

---

## Methodology

- Load and preprocess MNIST dataset (normalize pixel values, reshape inputs).
- Construct CNN with 4 convolutional layers, batch normalization, ReLU activation, and a global average pooling layer.
- Train the model using stochastic gradient descent optimizer.
- Evaluate model performance on test data.

---

## Results and Key Findings

- Training accuracy: approximately 91%
- Test accuracy: approximately 93%
- The CNN effectively learned to classify digits with strong accuracy.

---

## Visualizations

The project includes visualizations of handwritten digits alongside their predicted labels using heatmaps and images in the Jupyter notebook.

---

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- Seaborn

### Installation

Install the required Python packages using pip:

```bash
pip install -r requirements.txt
