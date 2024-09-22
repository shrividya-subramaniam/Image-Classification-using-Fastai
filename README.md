# Image-Classification-using-Fastai
Classification of Images into Cats and Dogs using the [dataset](https://www.kaggle.com/c/dogs-vs-cats/data) from Kaggle Competition [Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/overview)


## Problem Statement
The objective is to predict whether an image is a dog or a cat. 


## Evaluation Metric
Evaluation metric is **accuracy** i.e. percentage of correctly classified images.


## Prediction Approach
1. Move the images from train folder into their respective folders i.e cats and dogs for the images to be identified with their labels.
2. Create a DataLoader for the training set.
3. Apply data augmentation on the images to transform them.
4. Train the model by creating a Learner using ResNet18.
5. Create a confusion matrix to visualize the incorrect predictions of the model.
6. Create a test DataLoader
7. Predict the test results.

The model achieves an accuracy of 98.8% in 3 epochs. 
