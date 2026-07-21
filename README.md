# Handwritten Character Recognition using CNN

## Overview

This project implements a Convolutional Neural Network (CNN) for handwritten character recognition using the MNIST and EMNIST datasets. The model is trained to classify handwritten digits and letters, and its performance is evaluated using standard classification metrics.

---

## Features

- Image preprocessing and normalization
- CNN-based handwritten character recognition
- Training and evaluation on two benchmark datasets
- Performance comparison between MNIST and EMNIST
- Visualization of training history and prediction results

---

## Datasets

- **MNIST** – Handwritten digit recognition (0–9)
- **EMNIST (Letters)** – Handwritten English alphabet recognition

---

## Model Architecture

- Convolutional Neural Network (CNN)
- ReLU Activation
- Max Pooling
- Dropout
- Fully Connected Layers
- Softmax Output

---

## Results

| Dataset | Test Accuracy |
|---------|--------------:|
| MNIST | **99.20%** |
| EMNIST | **91.73%** |

The CNN achieved excellent performance on both datasets. As expected, EMNIST is more challenging due to the greater number of classes and visually similar handwritten letters.

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Project Structure



## How to Run

1. Clone the repository.
2. Install the required dependencies.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells to train and evaluate the CNN model.

