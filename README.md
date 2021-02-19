# HeartDiseaseClassificatiion

# Predict Heart Disease Using Machine Learning

This notebook looks into using various Python - based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medicasl attributes

We're going to take the following approach
1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## Problem Definition 

In a statement
> Given clinical parameters about a patient can we predict whether or not they have a heart disease?

## Data


This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them. In particular, the Cleveland database is the only one that has been used by ML researchers to
this date. The "goal" field refers to the presence of heart disease in the patient. It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).




> There is a version available in kaggle :https://www.kaggle.com/ronitf/heart-disease-uci
> The original dataset came from the Cleveland Data from the UCI Machine Learning Repository :https://archive.ics.uci.edu/ml/datasets/heart+disease


## Evaluation:

> If we can reach 95% accuracy at predicting whether a patient has heart disease during the proof of concept , we will pursue the project


## Features:

>This is where you get different information about each of the feature in your data

**Data Dictionary**

1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect



I have preprocessed and thoroughly explored the data. I have used various classification models out which Logistic Regression has emerged as a clear winner.
