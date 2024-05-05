# Pattern Recognition  System For Hand-Written Digits

# BM40A0702 Pattern Recognition and Machine Learning

## Group 15
Professor: Lasse Lensu  
Supervised by: Dr. Ekaterina Nepovinnykh  
Authors: Bipul Biswas, Jhuma Mim

## Project: Digits 3-D - Develop A Pattern Recognition System For Hand-Written Digits
The goal of this project is to develop a pattern recognition system for handwritten digits {0, 1, ..., 9} based on the time series representing the 3-D location. Python was used as the programming language for this project.

## Introduction
The project involves data processing and feature extraction, where the dataset is read using the panda's data frame library. The dataset is divided into two columns, instruction and label, and processed into an 80% train and 20% test split.

## Classification
A built-in python classifier Logistic Regression using Scikit library was used as a baseline for comparing our developed classifier. We ran our developed own LR and NN classifier and compared the result with the baseline classifier.

## Methodology
### Build Own LR classifier from scratch
We used the Gradient Descent algorithm for optimum values of m and c of the LR. We got the best-fit line using the values of m and c. We used a Loss function and made predictions. Error Analysis was also conducted.

### NN classifier development
We used two hidden and an output layer. We used a Loss function to calculate the gradient by applying the chain rule. We used gradient descent for updating weights. We used
 
