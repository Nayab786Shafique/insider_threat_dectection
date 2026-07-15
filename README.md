Insider Threat Detection using Machine Learning
About the Project
This project aims to enhance organizational security by identifying potential insider threats. It uses machine learning classification to analyze employee activity data and categorize them as either Malicious or Non-Malicious.
Key Features
Data Analysis: Processed and cleaned employee activity datasets.
Machine Learning Models: Implemented and compared four classification algorithms:
Decision Tree Classification

Random Forest Classification
Support Vector Machine (SVM)
Multi-Layer Perceptron (MLP)
--- Final Model Comparison Table ---
       Model  Accuracy  AUC Score
         MLP      0.97       0.99
RandomForest      0.97       0.98
         SVM      0.97       0.91
DecisionTree      0.97       0.79
Objective: To help companies proactively identify risks posed by internal users.
Tools & Technologies
Language: Python
Environment: Jupyter Notebook
Dataset: insider_threat_clean_dataset.xlsx
How to use
Clone this repository.
Open the threat_detection.ipynb file in Jupyter Notebook.
Ensure the dataset file is in the same directory.
