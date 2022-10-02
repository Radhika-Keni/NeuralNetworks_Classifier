# Classifying_MultiDigits_With_NeuralNetworks
Build a Digit Classifier 



## Objective of this notebook
- The purpose of this notebook is to build a Digit Image classifier the Street View Housing Number dataset.
- Details of the **problem statement**  , **data set** ,**sample input**, **summary of the code/solution** and **final result** of the project are listed in the sections to follow.

## Problem Statement 
A Recognising multi-digit numbers in photographs captured at street level is an important component of modern-day map making. A classic example of a corpus of such street-level photographs is Google’s Street View imagery composed of hundreds of millions of geo-located 360-degree panoramic images.


## Data Description:
The SVHN is a real-world image dataset for developing machine learning and object 
recognition algorithms with the minimal requirement on data formatting but comes from a significantly harder, 
unsolved, real-world problem (recognising digits and numbers in natural scene images). SVHN is obtained from 
house numbers in Google Street View images.
Where the labels for each of this image are the prominent number in that image i.e. 2,6,7 and 4 respectively.
The dataset has been provided in the form of h5py files. 

## Domain:
Autonomous Vehicles

## Sample Input
![image](https://user-images.githubusercontent.com/68383273/193480521-f3e3b769-294e-4367-846f-e2f11bcc0dae.png)


## Summary of the Solution/Code:
The code aims at building a digit(Image) Classifier classifier
- We begin by doing an Exploratory Data analyses and Visualisation/viewing of the images 
- We then do the required pre-processing of the data to prepare it so it can be fed into a Neural Network which involves converting target variable into a one hot   vector and normalising the input data 
- We then begin the process of building a Neural Network model 
- Next we  start "tuning" the model in terms of no of layers,adding L2 regularization parameter,adding batch normalisation layers & Drop out and for each of these cases , we capture the test data accuracy
- Finally we compare the test/validation accuracy for all the various models built above and choose the best contender
- Refer **python worksheet Project_ClassificationUsingNeuralNetworks_MultiDigitNumbers.ipynb** for the solution


## Result
![image](https://user-images.githubusercontent.com/68383273/193480475-5ceb88a2-2ed0-4d27-8b6d-82469317f1f6.png)




