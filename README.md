# Customer Churn Prediction using Logistic Regression

## Project Overview

This project uses Logistic Regression to predict whether a telecom customer is likely to churn or stay with the company.

This project demonstrates a complete beginner-level Machine Learning workflow for binary classification.

## Dataset

The dataset used in this project is the Telco Customer Churn dataset.

It contains customer information such as tenure, monthly charges, total charges, and churn status.

## Features Used

The following features were used to train the Logistic Regression model:

- Tenure
- Monthly Charges
- Total Charges

## Target Variable

The target variable is **Churn**.

- 0 → Customer Stayed
- 1 → Customer Churned

## Machine Learning Workflow

1. Define the Problem
2. Collect Dataset
3. Load Dataset
4. Explore the Dataset
5. Handle Missing Values
6. Select Features and Target
7. Split into Training and Testing Sets
8. Feature Scaling using StandardScaler
9. Train Logistic Regression Model
10. Learn Weights and Intercept
11. Predict Churn Probabilities
12. Convert Probabilities into Classes using Threshold
13. Evaluate the Model
14. Interpret the Results

## Model Evaluation

| Metric | Score |
|---|---:|
| Accuracy | 77.90% |
| Precision | 62.35% |
| Recall | 42.51% |
| F1 Score | 50.56% |
| ROC-AUC | 79.98% |

## Confusion Matrix

```text
[[937, 96],
 [215, 159]]

## Keep Learning

This project helped me understand how Logistic Regression can be used for binary classification.

I learned about data preprocessing, feature scaling, model training, probability prediction, threshold-based classification, and model evaluation using Accuracy, Precision, Recall, F1 Score, and ROC-AUC.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Project Files

- `Customer_Churn_Logistic_Regression.ipynb` — Complete project notebook
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — Dataset

## Conclusion

The Logistic Regression model achieved an accuracy of 77.90% and a ROC-AUC score of 79.98%.

This project helped me understand the complete Machine Learning workflow for a binary classification problem using Logistic Regression.
