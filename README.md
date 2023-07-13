# Image-Classification-using-CNN
This repository contains the code and resources for an image classification project aimed at classifying images into authentic and tampered categories using deep learning techniques.

## Project Overview
The goal of this project is to develop an accurate image classification model to identify authentic and tampered images. Two approaches were implemented: a normal CNN model built from scratch and transfer learning using the EfficientNetV2L pre-trained model.

## Dataset
The dataset used for this project consists of 1200 images, obtained by truncating a larger dataset. The source of the dataset is https://ieee-dataport.org/documents/fidac-forged-images-detection-and-classification.

## Approach
### Normal CNN Model:
Developed a custom CNN architecture comprising of convolutional, pooling, and fully connected layers.
Achieved a 70% accuracy on the test set.
### Transfer Learning:
+ Utilized the EfficientNetV2L pre-trained model as the base model.
+ Fine-tuned the model by freezing lower layers and adapting the output layer for binary classification.
+ Achieved an improved accuracy of 85% on the test set.
### Evaluation
The models were evaluated using accuracy, precision, recall, and AUC metrics. The evaluation results confirmed the effectiveness of both approaches in accurately classifying authentic and tampered images.

## Dependencies
The implementation of this project requires the following dependencies:

+ Python 3.x
+ TensorFlow
+ Keras
