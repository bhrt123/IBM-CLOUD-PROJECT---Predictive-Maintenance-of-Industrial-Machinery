# IBM-CLOUD-PROJECT---Predictive-Maintenance-of-Industrial-Machinery
Complete Project Files - FINAL PROJECT FOR IBM SKILLSBUILD INTERNSHIP DONE ON IBM CLOUD - IBM WATSON STUDIO


Develop a predictive maintenance model for a fleet of industrial machines to anticipate failures before they occur. This project will involve analyzing sensor data from machinery to identify patterns that precede a failure. The goal is to create a classification model that can predict the type of failure (e.g., tool wear, heat dissipation, power failure) based on real-time operational data. This will enable proactive maintenance, reducing downtime and operational costs. 

The solution will consist of the following components:
Data Collection:
Use Kaggle Dataset on Machine Predictive Maintenance Classification.
Data Preprocessing:
Clean and preprocess the collected data to handle missing values, outliers, and inconsistencies.
Feature engineering to extract relevant features from the data that might impact bike demand.
Machine Learning Algorithm:
Implement a machine learning algorithm, such as a classification model like Random Forest Classifier or Decision Tree
Evaluation:
Validate the model using Accuracy, precision, recall, f1-score, etc


The overall approach for developing and implementing the  “Predictive Maintenance of Industrial Machinery” system are:
System requirements:
IBM Cloud
IBM Watson Studio
IBM Cloud Object Storage for Dataset Handling
Models Used:
Random Forest Classifier and its variations
Decision Tree and its variation


Algorithm Selection:
Various pipelines with different base algorithm and modifications will be performed and the one with the best accuracy will be chosen.
Data Input:
Kaggle dataset “Machine Predictive Maintenance Classification” has the following data columns: 
Product Type, Air temperature [Kelvin], Process temperature [Kelvin], Rotational speed [rpm], Torque [Nm], Tool wear [min], Target
Training Process:
IBM Watson Studio powered - “Automatic Machine Learning Model Build” option.
Follows supervised learning using the input data and the label entry “Failure Type”.
Prediction Process:
Model deployed on IBM Watson studio with API endpoint for real-time predictions.
