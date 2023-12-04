# BME3053C-FinalProject-NeuronaviGATORS-
This project, developed by the NeuronaviGATORS team, leverages the power of Convolutional Neural Networks (CNNs) to classify MRI brain tumor images. The project utilizes MATLAB and a dataset acquired from Kaggle, featuring various types of brain tumors. Our approach involves preprocessing the image data, implementing a custom CNN architecture adapted from ResNet50, and training the model on a comprehensive dataset. The model demonstrates high accuracy in classifying different types of brain tumors, contributing significantly to the field of medical image analysis. This repository contains the complete codebase, dataset references, and detailed documentation.
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

# MRI Brain Tumor Classification using Convolutional Neural Networks

## Introduction
This project implements a Convolutional Neural Network (CNN) for classifying MRI brain tumor images using MATLAB. Designed by the NeuronaviGATORS team, it aims to automate and enhance the accuracy of brain tumor classification in medical diagnostics.

## Getting Started

### Prerequisites
- MATLAB (with Deep Learning Toolbox)
- Access to the dataset (provided in the Kaggle database)

### Installation
1. Clone the repository to your local machine
2. Download the dataset from Kaggle and place it in the designated folder within the project directory.

### Dataset Structure
Ensure your dataset is structured as follows:
- A main directory (e.g., `MRI Data Set`) containing two subdirectories: `Training` and `Testing`.
- Each subdirectory should contain images categorized into respective folders: `gliomas`, `meningiomas`, `pituitary tumors`, and `no tumors`.

## Running the Code

### Data Preparation
1. Open MATLAB and navigate to the project directory.
2. Run the initial setup script (if provided) to set up the environment and necessary variables.

### Training the Model
1. Execute the training script
2. The script will preprocess the data, initialize the CNN model, and start the training process.
3. Training progress will be displayed in MATLAB's command window.

### Testing the Model
1. After training, run the testing script
2. The script will use the trained model to classify the images in the testing dataset.
3. The output will include a confusion matrix and other performance metrics.

### Evaluating Results
- Review the confusion matrix and accuracy metrics to assess the model's performance.
- Sample predictions will be displayed, showing the model's classification results on test images.

## Troubleshooting
- If you encounter issues, check MATLAB's console for error messages, which often provide insights into what needs fixing.
