# Advanced Handwritten Digit Recognition using CNN

## Overview
This project builds an enhanced Convolutional Neural Network (CNN) to classify handwritten digits (0–9) from the MNIST dataset, with data augmentation and custom input prediction.

## Features
- Data Augmentation for better generalization
- Batch Normalization and Dropout to prevent overfitting
- Predicts real-world custom digit images
- Achieved Test Accuracy: ~99%

## Technologies Used
- Python
- TensorFlow & Keras
- OpenCV
- NumPy
- Matplotlib

## How to Run
1. Clone the repository
2. Install required libraries:
    ```
    pip install -r requirements.txt
    ```
3. Run the notebook `advanced_mnist_digit_recognition.ipynb`
4. For custom image prediction:
    - Add a grayscale 28x28 PNG image
    - Use `predict_custom_image('your_image.png')`

