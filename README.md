Road Accident Prediction System
Overview
The Road Accident Prediction System uses machine learning to predict the severity of road accidents (Fatal Injury, Serious Injury, or Slight Injury) based on various features such as driver details, vehicle conditions, road conditions, and environmental factors. The system leverages a trained Random Forest Classifier within a robust data processing pipeline for accurate predictions.

Features

Prediction of Accident Severity: Predicts the severity level of an accident.

Interactive Web Application: Built with Streamlit, the app allows users to input various parameters interactively.

Automated Data Preprocessing:
Missing value handling.
Encoding of categorical variables.
Feature selection using Chi-square statistics.

Machine Learning Pipeline:
Implements a RandomForestClassifier integrated into a pipeline for seamless preprocessing and predictions.
Imbalanced Data Handling: Uses oversampling to balance the dataset.

Technologies Used
Programming Language: Python
Libraries:
Machine Learning: scikit-learn, imbalanced-learn
Data Manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Web Interface: streamlit
Model: Random Forest Classifier
Deployment: Streamlit-based web application

