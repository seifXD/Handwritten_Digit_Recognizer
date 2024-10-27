# Handwritten Number Recognizer

## Project Overview

The **Handwritten Number Recognizer** is a machine learning project designed to accurately identify handwritten digits from the MNIST dataset, which consists of 70,000 images of handwritten numbers (0-9). This project employs deep learning techniques, specifically convolutional neural networks (CNNs), to train a model that can classify the digits with high accuracy.

## Dataset

The MNIST dataset contains 60,000 training images and 10,000 test images, each 28x28 pixels in grayscale. The dataset is widely used in the field of machine learning and serves as a benchmark for evaluating the performance of various algorithms in image recognition.

## Objectives

- To develop a robust model that can recognize handwritten digits with high accuracy.
- To explore various model architectures and hyperparameters to optimize performance.
- To visualize the model's performance through accuracy and loss graphs.

## Key Features

- **Data Preprocessing**: The raw images are preprocessed to enhance model performance. This includes normalization, resizing, and reshaping of image data.
- **Model Architecture**: A Convolutional Neural Network (CNN) is implemented to learn features from the images and classify them into one of ten categories (0-9).
- **Training & Evaluation**: The model is trained on the training set and evaluated on the test set, with metrics such as accuracy and loss recorded throughout the process.
- **Visualization**: Graphs displaying training and validation accuracy and loss are generated to analyze model performance and identify potential overfitting.

## Getting Started

To get started with the Handwritten Number Recognizer, clone this repository and install the necessary dependencies:

```bash
git clone <repository-url>
cd handwritten-number-recognizer
pip install -r requirements.txt
