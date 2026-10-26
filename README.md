# Pneumonia Detection using CNN

## Overview

This project is a simple implementation of a Convolutional Neural Network (CNN) to classify chest X-ray images as either **Normal** or **Pneumonia**. It demonstrates the basic workflow of building and training a CNN for image classification using TensorFlow and Keras.

## Dataset

The project uses the **Chest X-Ray Images (Pneumonia)** dataset from Kaggle:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

The dataset contains:
- 5,863 chest X-ray images
- Two classes:
  - Normal
  - Pneumonia

The data is divided into three folders:
- Train
- Validation
- Test

Each folder contains images for both the **Normal** and **Pneumonia** classes.

## Preprocessing

The following preprocessing steps were performed:
- Loaded the dataset
- Resized the images to a fixed size
- Normalized the pixel values
- Prepared the data for training and testing

## CNN Architecture

The model consists of the following layers:
1. Convolutional Layer
2. Max Pooling Layer
3. Flatten Layer
4. Dense (Fully Connected) Layer
5. Output Layer

Since this is a binary classification problem, a **Sigmoid** activation function is used in the output layer to predict whether an X-ray image is **Normal** or **Pneumonia**.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Files

- `model.ipynb` – Model training and evaluation
- `new_data_test.ipynb` – Testing the model on new images
- `requirements.txt` – Project dependencies

*The dataset and trained model files are not included in this repository because of their size. P

