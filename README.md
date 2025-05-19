Heart Failure Prediction Using Azure ML – Capstone Project
This project, part of the Microsoft Azure Machine Learning Nanodegree, aims to predict heart failure using a dataset from Kaggle. It involves training two types of models in Azure ML Studio: an AutoML Voting Ensemble model and a custom Logistic Regression model tuned via HyperDrive. The AutoML model achieved the best performance with 87.6% accuracy and was deployed as a web service using Azure Container Instance. The Logistic Regression model achieved 81.7% accuracy after hyperparameter tuning. The deployed model can be accessed via REST API, and Application Insights was enabled for monitoring.

Key tools used: Azure ML SDK, AutoML, HyperDrive, Azure Container Instance, REST API
Dataset: 299 patient records, 13 medical features
Task: Binary classification to predict mortality from heart failure
