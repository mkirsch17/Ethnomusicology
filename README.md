# Ethnomusicology
This project aims to predict the continent of origin of "world" music by implementing three machine learning techniques:
1. Logistic regression
2. SVM
3. Neural network

## Requirements
* pandas=1.0.3
* scikit-learn=0.22.1
* numpy=1.18.1
* pytorch=1.4.0
* seaborn=0.10.0
* matplotlib=3.1.3

## Methods
The dataset used for this project comes from a 2014 publication titled ["Predicting the Geographical Origin of Music"](https://ieeexplore.ieee.org/document/7023456), and was accessed via the [UC Irivine Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Geographical+Original+of+Music). In order to tackle this as a classification problem, each song's geographic coordinates were mapped to its continent of origin, which is performed by "get_song_continent.ipynb".

## Instructions
Each method, as outlined above, runs on a standalone Jupyter Notebook script. Simply run each script to obtain the accuracies of each model.

## Results
Across the three models, we found that a support vector machine using an RBF kernel was the most accurate at 63% accuracy.
