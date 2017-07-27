# Predicting-with-R---

## Synopsis
The goal of this project is to predict the manner in which the subjects have done the exercise. We have two sets provided, training and testing. There is a "classe" variable in the training set which will be used with any of the other variables to train the model. We will later use the prediction model to predict 20 different test cases.

## Introduction
In this stage, we will be reading the training data and focusing our predictor variables to be the accelerometer data on the belt, forearm and dumbell in x, y and z directions. We will be chosing only those cases where we have complete information available. No NaN's 

# Data Analysis
Given that we have a number of variables, we will check the correlation between each of them. 

# Split the data set 
Let us now work to build a model on the training set. We split this set into training (75%) and testing (25%). Model will be built on this training set and errors will be decided on the test set. 

# Fit models.
We select two models to fit with one with tree bag method and other with Random forest. 


# Predict the models on the test set 
Using the predict function, we now see the performance of both the models on the test set. 

# Out of Bag Error.
We will calculate the out of bag error

# Test the models on the actual testing set. 

Let build the same models on the actual training set. 

# Plot the models

# Predict on test set. 

Load the testing set and predict on that set using the models

Check the error between the results of the two models. 


