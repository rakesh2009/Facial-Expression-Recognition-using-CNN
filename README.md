# Facial-Expression-Recognition-using-CNN
Finding the facial emotions of image using CNN

## Problem Statement

The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

## Dataset Description:

Total Images: The dataset consists of 28,709 examples

Fer2013.csv contains two columns, "emotion" and "pixels". The "emotion" column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The "pixels" column contains a string surrounded in quotes for each image. 

**Classes: 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral**

## Tasks performed:

As a part of this work I performed the following tasks:

a) Prepared a detailed python notebook using convolutional neural network for classifing the images from Fer.csv

b) **Reshape the data:**

 • Splitted pixels by space to get columns

 • reshape the input image (48, 48 ,1)

 • changed the type of data to float32
 
c) **Normalize & Train_Test Split:**

• Normalized the data by dividing with 255

• Splitted the data into train and test (90,10)

d) Model building

e) Evaluating the performance of model using plots and displaying the predicted emotions againt the images


## Dependencies:

Python 3+, jupyter notebbook, Pandas, Numpy, Tensorflow, Keras, Matplotlib

## Purpose:

The purpose of this project is to gain insights, capability building & developing competency in 

a) Pratical implementation of CNN using Tensorflow and keras 

b) Finding the different emotions of test images using the trained model

c) Tuning of hyperparameters in deep neural network
