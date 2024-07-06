# Mental Health Client-Level Data (MH-CLD)

This project is a part of the ADS-XXX course in the Applied Data Science Program at the University of San Diego. 
-- Project Status: Completed

Dataset can be found at:
https://www.datafiles.samhsa.gov/dataset/mental-health-client-level-data-2020-mh-cld-2020-ds0001

## Project Intro/Objective

The main purpose of this project is to forecast the diagnosis of trauma- and stressor-related disorder. Using Mental Health Client-Level Data (MH-CLD), this project seeks to serve as a tool to expedite time associated with the referral process getting patients with the appropriate healthcare professionals.

## Methods Used
•	Inferential Statistics
•	Predictive Modeling 
•	Machine Learning
•	Data Visualization

## Technologies
•	Python

## Project Description

The data used for this project was attained from the Substance Abuse and Mental Health Services Adminsitration using the MH-CLD and the Mental Health Treatment Episode Data Set (MH-TEDS). After conducting an exploratory data analysis, six supervised machine learning models (logistic regression, random forest, random vector machine, neural networks, K-nn, and gradient boosting) were built to predict the diagnosis of Trauma- and stressor-related disorder. As indicated below with the results, the neural network had the best performance when comparing specificity, sensitivity, and F1 score.

Model Type: Specificity, Sensitivity, F1 Score

Neural Network:	0.988539	0.981054	0.983891 

Support Vector: Machine	0.892550	0.877265	0.876904

Random Forest:	0.905444	0.771005	0.820333

KNN:	0.859599	0.795717	0.813131

Gradient Boosting:	0.800143	0.719934	0.738488

Logistic Regression:	0.670487	0.584020	0.595048
