# Signature Forgery Detection with One-shot Learning

## Description

Conventional deep learning methods require large samples of data for a class in the classification process. One shot learning, being a method of meta learning, can perform classification tasks with one data point. Hence for the tasks like facial recognition, audio recognition, signature forgery verification this method of meta learning becomes more suitable at industrial level. For our project we performed signature forgery: identifying if a signature has been forged or otherwise.

## Main features

- Compare signatures and detect if they have been forged or not
- Can also work on new data without retraining
- Works with the accuracy of ~99%

## Tech Stack and concepts used

- Python
- Keras
- OpenCV
- Matplotlib
- Scikit-learn
- Convolution Neural Network
- Siamese Neural Network

##  Thought behind the project

Using one-shot learning for signature forgery detection we can predict whether a signature has been forged or not using only one genuine signature for comparison without retraining the whole model. Also, one-shot learning models does not require huge datasets to train and can generalize very well. 

## Setup

- Download dataset and trained model from [here](https://drive.google.com/drive/folders/1RNOg9Au19eSA5xKd-Sx_GdAm6k1j-fCQ?usp=sharing) and upload it in your Google Drive
- Download and open [checking_forgery.ipynb](https://github.com/aniketsharma00411/one-shot-signature-forgery-detection/blob/main/checking_forgery.ipynb) using Google Colab.
- Use the notebook to check signature forgery.
