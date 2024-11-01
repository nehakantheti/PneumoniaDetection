# Pneumonia Detection Using Images

This project focuses on developing a deep learning model to detect pneumonia from chest X-ray images. Leveraging Convolutional Neural Networks (CNN) implemented with Keras and TensorFlow, we achieved an accuracy of 82% on the test dataset.

## Introduction

Pneumonia is a severe respiratory condition that can be life-threatening, especially in vulnerable populations. Early detection plays a crucial role in treatment and recovery. In this project, we aimed to create an automated system for pneumonia detection using chest X-ray images, harnessing the power of deep learning techniques.

## Dataset

The dataset used in this project is a publicly available collection of chest X-ray images. It includes images labeled as pneumonia and normal, allowing the model to learn distinguishing features. Training size for this model is around 3875 and test size is 1341.

## Model Architecture

We utilized a Convolutional Neural Network (CNN) for image classification. The model consists of multiple convolutional layers, pooling layers, and fully connected layers, optimized to learn patterns in the X-ray images effectively.

## Installation

To run this project, you will need to install the following libraries:

```bash
pip install tensorflow opencv-python matplotlib
