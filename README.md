# AI-CyberSecurity
This the the repository to save all the files for the AI and Cyber Security course.

# Phishing detetion models
This directory contains models for Clasifiers to detect Phishing for the UCI Phishing dataset [[Link]](https://archive.ics.uci.edu/ml/datasets/phishing+websites)
<br>Its contains python norebook files for four different models

* [LinearRegression](https://github.com/abhi5movva/AI-CyberSecurity/blob/main/Phishing_detection_models/AISec_Phishing_Linear_Regression.ipynb)
 <br> This notebook contains a simple classifier on Scikit-Learn LinearRegresion
  
 * [LogisticRegression](https://github.com/abhi5movva/AI-CyberSecurity/blob/main/Phishing_detection_models/AISec_Phishing_Logistic_Regression.ipynb)
 <br> This notebook contains a simple classifier on Scikit-Learn LogisticRegression
  
* [Support Vector Machine](https://github.com/abhi5movva/AI-CyberSecurity/blob/main/Phishing_detection_models/AISec_Phishing_SVM.ipynb)
<br>  This notebook contains a simple classifier on Scikit-Learn SVC classifier
  
 * [Perceptron](https://github.com/abhi5movva/AI-CyberSecurity/blob/main/Phishing_detection_models/AISec_Phishing_Perceptron.ipynb)
  <br>This notebook contains a simple classifier on Scikit-Learn Perceptron
  
  ### Common steps
  All the notebook has following steps
  - Load and split data into train and test set
  - Train a baseline model
  - Create interaction features since these models doesn't handle Interactions
  - Tune hyper-parameter
  - Keep only a limited number of features out of all the interaction features
