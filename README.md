Beta Bank Customer Churn Prediction Project Overview
Beta Bank is facing customer churn — clients are gradually leaving each month. Since retaining customers is cheaper than acquiring new ones, the goal is to predict whether a customer will leave the bank soon based on their past behavior. We need to build and evaluate a classification model to identify potential churners.
🎯 Objectives
	1. Build a machine learning model to predict customer churn.
	2. Achieve an F1 score ≥ 0.59 on the test set.
	3. Evaluate the AUC-ROC metric and compare it with F1.
🧩 Project Steps
Data Preparation: Download the prepare the dataset from /datasets/Churn.csv. Clean and preprocess the data as needed (encoding, scaling, etc.).
Initial Modeling: Explore class balance. Train a baseline model without handling class imbalance. Record and describe baseline performance.
Model Improvement:Apply at least two methods to address class imbalance (e.g., oversampling, undersampling, class weights). Train and tune multiple models using the training and validation sets. Select the best-performing model and document findings.
Final Evaluation: Test the chosen model on the test set. Report final F1 and AUC-ROC scores.
🧠 Dataset Description
Feature Description RowNumber Data index CustomerId Unique customer identifier Surname Customer surname CreditScore Credit score Geography Country of residence Gender Gender Age Age Tenure Years with the bank Balance Account balance NumOfProducts Number of banking products used HasCrCard Whether the customer has a credit card IsActiveMember Activeness status EstimatedSalary Estimated salary
🎯 Target Exited Customer has left (1 = customer left, 0 = stayed)
📈 Evaluation Metrics Primary: F1 Score (≥ 0.59 required) Secondary: AUC-ROC
<img width="1192" height="1384" alt="image" src="https://github.com/user-attachments/assets/7b6c0f64-b85c-4bbb-a5d7-2d79d83237de" />
