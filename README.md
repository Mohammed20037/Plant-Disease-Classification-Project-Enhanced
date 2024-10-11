# Plant Disease Classification Project

## Overview
This repository contains the code and dataset for a plant disease classification model. The project aims to identify various plant diseases based on images of plant leaves. This work is crucial for developing automated tools that help farmers and researchers quickly diagnose plant diseases.

## Dataset
The dataset consists of images representing multiple classes of plant diseases. Each class corresponds to a specific disease affecting certain plant species. The images used in this project are categorized into several classes, as illustrated in the histograms and images provided in this repository.

![Images per class] ![image](https://github.com/user-attachments/assets/b697cbc9-9101-4570-9592-886f6e40adfc)
![Sample leaf images](path_to_leaf_images)

## Principal Component Analysis
We have utilized PCA to reduce the dimensionality of our dataset and to better understand the underlying patterns in the data. The PCA scatter plot illustrates the variance and clustering of the data points.

![PCA Scatter Plot](path_to_pca_plot)

## Model Training
We have experimented with several machine learning models and optimization techniques to find the most effective approach for our classification task. The models evaluated include ResNet9, VGG16, and MobileNetV2. We have also compared different optimizers such as Adam, RMSprop, and SGD to optimize our models.

### Performance Comparison
The following plots show the validation accuracy and loss for different optimizers across epochs:
![Validation Accuracy](path_to_val_accuracy_plot)
![Validation Loss](path_to_val_loss_plot)

Here are the accuracy and loss metrics for the models used:
![Model Metrics](path_to_model_metrics_plot)

## Requirements
This project is implemented using Python. Required libraries include TensorFlow, Keras, NumPy, Matplotlib, and others. A detailed list of requirements can be found in `requirements.txt`.

## Usage
To use this model for classifying plant diseases, follow these steps:
1. Clone the repository:
