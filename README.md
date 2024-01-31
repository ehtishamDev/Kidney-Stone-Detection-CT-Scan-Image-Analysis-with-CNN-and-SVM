# Kidney-Stone-Detection-CT-Scan-Image-Analysis-with-CNN-and-SVM

## Overview
This project aims to classify CT scan images of kidneys as either containing kidney stones (positive) or not containing kidney stones (negative) using deep learning models. The dataset used contains 3000 CT images of kidneys split into training and validation sets. The images are categorized into two classes - 'Normal' (negative) and 'Stone' (positive).

## Models
The following deep learning models have been implemented and evaluated:

**Convolutional Neural Network (CNN)**
A CNN model with convolutional, max pooling and dense layers is built and trained on the preprocessed CT images to learn image features and classify images.

**Support Vector Machine (SVM)**
Histograms of Oriented Gradients (HOG) features are extracted from the images and an SVM classifier is trained on these features for classification.

## Data Preprocessing
The raw CT images are preprocessed as follows:

Images are resized to a fixed size for model input

Images are normalized

One-hot encoding is done for labels

Train-validation split is performed

## Training
Models are compiled and trained on the training set

Validation loss and accuracy are monitored during training

Models are saved if validation accuracy improves

## Evaluation
Trained models are evaluated on the validation set:

Validation accuracy

Confusion matrix

Classification report

## Usage
The notebook contains code to:

Prepare the dataset

Implement the CNN and SVM models

Train and evaluate the models

Make predictions on new images


## Requirements
Keras

TensorFlow

Scikit-learn

OpenCV

Numpy, Pandas, Matplotlib

## Screenshot of GUI
![GUI_Snapshot](https://github.com/ehtishamDev/Kidney-Stone-Detection-CT-Scan-Image-Analysis-with-CNN-and-SVM/assets/146319638/a772ed3c-760e-416a-a05a-b6b7ce4e9895)


