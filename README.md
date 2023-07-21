# Udacity_Machine_Learning
Udacity: Intro to Machine Learning course - wrap up

Author: ZUKHRIDDIN JULIEV

Date: July 21, 2023

This project is a general combination of application of all models covered during Intro to Machine Learning elective course.
The models ceovered are: Gaussian Naive Baese, SVM, Decision Trees, Random Forest, AdaBoost Classifier, KMeans and KNeighbors Classifier, Logistic Regression with regularization.

I have applied all models onto ENRON email data to predict person of interest within dataset. 
All models are first applied with default parametres. In the next stage I applied GridSearch CV to find the optimal parametres for each model to increase prediction power.

Result of prediction is evaluated using accuracy scores. The scores varied from 27% to 97%. Random Forest and SVM are the models with the greatest prediction power, although other models are also did nearly good. Among models KMeans and Gaussian NB are the least with prediction power. 
Additional to classification models, I also applied linear model with LASSO for the reference. The linear model is not appropriate since the target values are binary.

Files:
1. final_project_dataset_unix.pkl - Main data set
2. Intro_to_ML.ipynb - jupyter notebook with codes
3. Intro_to_ML.html - notebook with results
