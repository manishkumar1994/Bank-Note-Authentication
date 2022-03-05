# Bank Note Authentication End to End with Dockers

## Objective

In this project, the objective is to create a flask app to authenticate the Bank notes.

## Motivation

It's always my goal to find solutions to everyday problems using Data Sceince techniques. Recently, while working at a retail store as a part-time job, we began receiving a lot of fake notes, which created a lot of difficulties for the owner. Sometimes, it can be very difficult to tell if the note is genuine. After studying this, I tried to see how this problem could be solved and what all could be done to resolve it

## Introduction 

This Machine Learning Web Application uses a several features of Banknotes like variance, skewness, curtosis and entropy to predict the Authenticy of Banknotes weither it is Genuine or Forged with an accuracy of 99.02% using Random Forest Classifier.This Dataset is taken from UCI Repository and also available in Kaggle,Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were used to extract features from images,In this ml model we are considering 0 for geniune bank note and 1 for forged bank note.
## Dataset
https://archive.ics.uci.edu/ml/datasets/banknote+authentication
The features are variance skewness curtosis entropy and class
### Step 1
Created a model using Random forest and the accuracy received is 99%. As the accuracy is very high it may come under overfitting, however, I decided to continue with the same accuracy as I wanted to learn the docker concept to understand how I can execute the model properly in different environments.
### Step 2: 
Created flask app 
### Step 3: 
Tested in post man app 
### step 4
Created a front end using a flassger library.
### Step 4: 
1) Write a docker file
2) Building the docker image
3) Running the app
