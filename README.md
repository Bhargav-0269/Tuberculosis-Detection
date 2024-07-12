Tuberculosis Detection from Chest X-Rays

Introduction
This project aims to detect tuberculosis from chest X-ray images using deep learning techniques. It leverages convolutional neural networks (CNNs) to classify X-ray images as either showing signs of tuberculosis or not.

Table of Contents
Introduction
Table of Contents
Dataset
Installation
Usage
Model Architecture
Results
Contributing
License
Dataset
The dataset used in this project consists of chest X-ray images. You can download the dataset from Kaggle or any other relevant source. Make sure to organize your dataset into the following directory structure:

css

data/
    train/
        TB/
        Normal/
    test/
        TB/
        Normal/
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/Bhargav-0269/tuberculosis-detection.git
cd tuberculosis-detection
The model architecture is based on a convolutional neural network (CNN) with the following layers:

Convolutional layers
Max pooling layers
Fully connected layers
Dropout layers for regularization
You can find the detailed architecture in the model.py file.

Results
After training the model for 50 epochs, we achieved the following results:

Accuracy: 95%
Precision: 94%
Recall: 96%
F1 Score: 95%
