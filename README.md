# Beta Bank Customer Churn Prediction

## Project Overview
Beta Bank is facing customer churn — clients are gradually leaving each month. Retaining existing customers is more cost-effective than acquiring new ones. The goal of this project is to **predict whether a customer will leave the bank** based on their past behavior using a machine learning classification model.

## Objectives
- Build a machine learning model to predict customer churn.
- Achieve an **F1 score ≥ 0.59** on the test set.
- Evaluate and compare **AUC-ROC** with F1 as a secondary metric.

## Project Steps
1. **Data Preparation**
   - Download and prepare the dataset (`datasets/Churn.csv`).
   - Clean and preprocess data (encoding categorical variables, scaling numeric features, etc.).

2. **Initial Modeling**
   - Explore class balance.
   - Train a baseline model without handling class imbalance.
   - Record and analyze baseline performance.

3. **Model Improvement**
   - Apply at least two methods to handle class imbalance (e.g., oversampling, undersampling, class weights).
   - Train and tune multiple models using training and validation sets.
   - Select the best-performing model and document findings.

4. **Final Evaluation**
   - Test the selected model on the test set.
   - Report final **F1** and **AUC-ROC** scores.

## Dataset Description
| Feature | Description |
|---------|-------------|
| RowNumber | Data index |
| CustomerId | Unique customer identifier |
| Surname | Customer surname |
| CreditScore | Credit score |
| Geography | Country of residence |
| Gender | Gender |
| Age | Age |
| Tenure | Years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of banking products used |
| HasCrCard | Whether the customer has a credit card |
| IsActiveMember | Activeness status |
| EstimatedSalary | Estimated salary |

**Target:** `Exited` — Customer left the bank (1 = left, 0 = stayed)

## Evaluation Metrics
- **Primary:** F1 Score (goal ≥ 0.59)  
- **Secondary:** AUC-ROC
