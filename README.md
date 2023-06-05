# Melanoma Classification using SqueezeNet50
## Introduction
This project is a Python script for melanoma classification using the SqueezeNet50 deep learning model. Melanoma is a type of skin cancer, and early detection plays a crucial role in successful treatment. This script aims to assist in the early identification of melanoma by classifying skin lesion images as either malignant (melanoma) or benign (non-melanoma).

## Features
Utilizes the SqueezeNet50 deep learning model for accurate melanoma classification.
Supports both single image classification and batch processing of multiple images.
Provides classification results with probabilities for melanoma and non-melanoma classes.
Allows users to visualize the predicted probabilities and the predicted class label for each input image.
Can be easily integrated into other Python projects or used as a standalone script.

## Prerequisites
Before running the script, ensure that the following requirements are met:

- Python 3.7 or above
- Sklearn
- Numpy
- Matplotlib
- Wtfml
- Albumentations


Methods
SqueezeNet50 was trained on kaggle dataset along with additional, publicly sourced training data from past Kaggle competitions.
Hyperparameters were tuned through validation testing.


Acknowledgments
The SqueezeNet50 model used in this project was developed by researchers at DeepScale.
The melanoma dataset used for training the model was obtained from the International Skin Imaging Collaboration (ISIC) archive.
References
DeepScale. (2016). SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size. Retrieved from https://arxiv.org/abs/1602.07360
International Skin Imaging Collaboration (ISIC). (n.d.). Retrieved from https://www.isic-archive.com/