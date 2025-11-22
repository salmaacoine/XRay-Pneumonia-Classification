This repository contains a project for detecting pneumonia using chest X-ray images. The project utilizes convolutional neural networks (CNNs) to classify chest X-rays as either healthy or pneumonia-affected.

Table of Contents: -Project Overview -Dataset -Model Architecture -Results -Installation -Usage -Contributing

Project Overview: The goal of this project is to create a deep learning model capable of detecting pneumonia from chest X-ray images. Pneumonia is a serious lung infection, and early detection through X-ray analysis can improve treatment outcomes.

This model is trained using the Chest X-ray dataset, which contains labeled X-ray images categorized as either normal or pneumonia-affected.

Dataset: The dataset used in this project is the ChestX-ray dataset, which contains the following classes:

Normal: X-ray images of healthy lungs. Pneumonia: X-ray images of lungs affected by pneumonia. Dataset Structure The dataset is organized into three folders:

train/: Training images. val/: Validation images. test/: Testing images.
Model Architecture: The model uses a Convolutional Neural Network (CNN) for image classification, consisting of the following layers:

Convolutional layers for feature extraction. MaxPooling layers for downsampling. Fully connected dense layers for classification.

Model Summary: Input: Chest X-ray images Layers: Conv2D, MaxPooling, Flatten, Dense, Dropout Activation: ReLU, sigmoid Loss Function: Binary Crossentropy Optimizer: Adam

Results: Training Accuracy: 89% Validation Accuracy: 75% Test Accuracy: 75% Loss: 1.62

The model achieves high accuracy in detecting pneumonia, providing a useful tool for assisting medical diagnosis.

Made by ACOINE Salma, ACHOUKHI Razane

5IIR 11 

2025-2026
