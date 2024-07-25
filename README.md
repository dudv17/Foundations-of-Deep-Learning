# Deep Learning for Image Classification: A Study on CIFAR-10
This repository contains the project work for the Deep Learning course as part of the Master of Science program in Data Science at Università degli Studi di Milano-Bicocca. The project focuses on applying deep learning techniques to the CIFAR-10 dataset, a widely used benchmark in the field of machine learning and computer vision.

# Project Overview
The project explores different deep learning architectures for image classification. The dataset consists of 60,000 32x32 color images in 10 classes, with 50,000 training images and 10,000 test images. The main objectives of the project were to:

1. Preprocess and Analyze the Dataset: Standardizing images and performing exploratory data analysis to understand the dataset's structure and characteristics.
2. Develop and Evaluate Various Models:
  - A basic Convolutional Neural Network (CNN) to establish a baseline.
  - An improved CNN with additional layers and regularization techniques to overcome overfitting.
  - A deeper ResNet architecture to overcome the limitations of basic CNNs, such as the vanishing gradient problem.
  - Data Augmentation techniques to enhance model generalization and performance.
  - Transfer learning using pre-trained models like ResNet50v2 and EfficientNetV2S for enhanced performance.

# Results
| Models          | Accuracy | Loss   |
|-----------------|:--------:|--------|
|            CNN1 |  72.75%  | 0.8166 |
|            CNN2 |  80.88%  | 0.7564 |
|       res_model |  82.89%  | 0.9794 |
|   res_model_aug |  89.86%  | 0.5611 |
|      ResNet50V2 |  96.35%  | 0.1879 |
| EfficientNetV2S |  97.23%  | 0.1777 |
