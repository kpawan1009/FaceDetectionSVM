﻿# FaceDetectionSVM
 This is SVM Classifier which is trained on dataset created live using haar feature extraction techniques , HaarCascadeDefault to extract face from a image .
 The dataset used is created in realtime and stored as .npy file which is much faster as compared to .csv and .txt files .
 The model is trained and saved using pickle in local memory as my_model 
 The model gives an accuracy of around 92 percent on clear and bright images and accuracy is low when picture is in dim light .
 This is a model which gives output with realtime data as input taken from the primary camera of a device and can be used in many places to monitor mask wearing in       hospitals and not wearing in atm machines .
