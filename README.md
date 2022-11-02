# Earning Prediction

Machine Learning project from the Free University of Bozen-Bolzano. Developed together with Joerdis Krieger. The task was to formulate a prediction goal and to explore different machine learning models. Project consists of a jupyter notebook file, with in-depth detail explanations of each machine learning algorithm we used. Below follows a short overview. 

## Introduction 
The project consist of two prediction goals: 
- Predict whether a person makes over 50K a year (classification problem)
- Predict the age of a person (regression problem).

The dataset used is called "Adult Income", from 1996. Contains census data from about almost 50K individuals with 15 attributes. So information about age, education relationship and the target attribute whenever a person makes over 50k a year.

## Libraries and Framework 
We are using pandas and numpy as they provide efficient used for large dataaframe structures and prebuild functions. The Machine Learning methods are implemented with sklearn. 

## Workflow 
As the well known slogan "Your Predictions Are Only As Good As Your Data" suggest, we preformed data preprocessing before applying the ML models. A split of the data set was also performed. 20% test data. Dataset was  balanced, since around 75% of the sample data earned less then 50k. ML methods could therefore be evaluated with accuracy and a confusion matrix, showing true negatives, true postives etc... 

