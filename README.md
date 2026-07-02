
# MNIST Handwritten Digit Recognition using TensorFlow

## Overview

This project implements a **Handwritten Digit Recognition System** using **TensorFlow** and **Keras**. A deep neural network is trained on the **MNIST** dataset to classify handwritten digits (0–9) with high accuracy.

---

## Features

* Reads the MNIST dataset from CSV files
* Preprocesses and normalizes image data
* Builds a Deep Neural Network (DNN)
* Trains and evaluates the model
* Predicts handwritten digits
* Displays prediction results and training graphs
* Saves the trained model for future use

---

## Dataset

**Kaggle Dataset (CSV):**
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

Dataset Files:

* `mnist_train.csv` – 60,000 training images
* `mnist_test.csv` – 10,000 testing images

Each image is a **28 × 28 grayscale image (784 pixels)**, and the first column contains the digit label (0–9).

---

## Technologies Used

* Python
* TensorFlow
* Keras
* Pandas
* NumPy
* Matplotlib

---

## Why TensorFlow?

TensorFlow is used to:

* Build the neural network
* Train the model efficiently
* Automatically perform backpropagation
* Optimize weights using the Adam optimizer
* Evaluate model performance
* Predict handwritten digits
* Save the trained model

TensorFlow simplifies deep learning development by handling the complex mathematical computations internally.

---

## Model Architecture

```text
Input Layer (784)
        │
Dense (256, ReLU)
        │
Dropout (0.3)
        │
Dense (128, ReLU)
        │
Dense (64, ReLU)
        │
Output Layer (10, Softmax)
```

---

## Workflow

```text
Load Dataset
      ↓
Preprocess Data
      ↓
Build Model
      ↓
Train Model
      ↓
Evaluate Model
      ↓
Predict Digits
      ↓
Save Model
```

---

## Results

* Training Accuracy: ~99%
* Test Accuracy: ~97–99%

---

## Applications

* Optical Character Recognition (OCR)
* Bank cheque digit recognition
* Postal code recognition
* Form digitization
* Handwritten document processing

---

## Future Improvements

* Implement a Convolutional Neural Network (CNN)
* Develop a Streamlit web application
* Deploy the trained model to the cloud
* Allow users to upload handwritten digit images for prediction

---

## Conclusion

This project demonstrates how TensorFlow can be used to build, train, and evaluate a deep learning model for handwritten digit recognition. It provides a solid foundation for learning neural networks and image classification while showcasing the complete deep learning workflow.
