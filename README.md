# Credit Card Fraud Detection 


*Data Source: The dataset was collected from credit card transactions made by European cardholders in 2023, with sensitive information removed to ensure privacy and compliance with ethical guidelines.*
https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023

## Goal: 
- Perform exploratory data analysis using data science techniques in Python/Jupyter Notebook and build machine-learning models for detecting credit-card frauds.

## Results:
- Initially, I experimented with a simple subset of features, `V1-V5`, for our classification model, resulting in a **6.6%** misclassification rate. While this provided a baseline, I sought to improve model performance further.

- I then explored more advanced techniques, including a **Bagging Classification model**, which achieved a significant reduction in the misclassification rate to just **0.06%** using all `V1-V28` features. This improvement demonstrated the value of ensemble methods in handling complex classification tasks.

- Subsequently, I employed a **Random Forest Classification model** with all `V1-V28` features, which further enhanced performance with a remarkable **0.01%** misclassification rate. The Random Forest's ability to capture complex relationships within the data was a key contributor to this achievement.

- The top 3 anonymized features that were most significant were `V1, V10, V14`.
