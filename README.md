# Intel-Image-Classification

In This project , A power Convolutional Neural Network has been implemented to classify different sets of images with higher accuracy

# Project Overview

### DataSet Description
The dataset contains image data of Natural Scenes around the world.

This Data contains around 25k images of size 150x150 distributed under 6 categories.

{'buildings' : 0,
'forest' : 1,
'glacier' : 2,
'mountain' : 3,
'sea' : 4,
'street' : 5 }

The Train, Test and Prediction data is separated in each zip files. There are around 14k images in Train, 3k in Test and 7k in Prediction.

### Importing all the necessary libraries
All the below libraries have been used in this project

1. tensorflow
2. keras
3. matplotlib
4. seaborn
5. pathlib
6. os
7. random
8. numpy

### Understand the Data set

1. check the distribution of different classes in the training data
2. Read and store all the images from the training, testing and prediction data folder
3. Visualize different images from different classes

### Model Creation

1. At first Data Augmentation is applied on the train and test images to avoid overfitting
2. A CNN model is created with 4 convolution layers.
3. The output of the last convolution layer has been flattened and applied into a fully connected Dense Neural Network.
4. The training and testing output has been observed and plotted.
5. The model is then applied on some new images to predict their classes.

