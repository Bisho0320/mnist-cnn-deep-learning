# Handwritten Digit Recognition using CNN (MNIST)

## Project Description

This project implements a Deep Learning model using Convolutional Neural Networks (CNN) for handwritten digit recognition on the MNIST dataset.

The project was developed as part of the Deep Learning Course requirements. Two experiments were conducted using different optimizers (Adam and SGD) to compare model performance.

---

# Dataset

The project uses the MNIST dataset, which contains handwritten digit images from 0 to 9.

Dataset Link:

[MNIST Dataset](https://www.tensorflow.org/datasets/catalog/mnist?utm_source=chatgpt.com)

---

# Technologies Used

- Python
- TensorFlow
- Keras
- Matplotlib

---

# Data Preprocessing

The following preprocessing steps were applied:

- Normalization
- Reshaping images to (28,28,1)
- Training and testing split

---

# Model Architecture

The CNN model consists of:

- Conv2D Layer
- MaxPooling2D Layer
- Conv2D Layer
- MaxPooling2D Layer
- Flatten Layer
- Dense Layer
- Dropout Layer
- Output Layer (Softmax)

---

# Experiments

## Experiment 1
- Optimizer: Adam

## Experiment 2
- Optimizer: SGD

Both experiments used:
- Epochs = 10
- Batch Size = 32

---

# Results Comparison

| Model | Optimizer | Accuracy | Loss |
|---|---|---|---|
| CNN Model A | Adam | 99.22% | 0.0279 |
| CNN Model B | SGD | 98.31% | 0.0525 |

---

# Conclusion

The CNN model trained with the Adam optimizer achieved better performance than the SGD optimizer. Adam provided higher accuracy and lower loss on the MNIST dataset.

---

# Visualizations

The project includes:
- Training vs Validation Loss Curves
- Training vs Validation Accuracy Curves

---

# How to Run

## Install Requirements

```bash
pip install tensorflow matplotlib