# Telecom-Churn-Prediction
“End-to-end ML classification project on telecom churn including EDA, SMOTE balancing, and model tuning.”
Project Overview

Customer churn is a major challenge in the telecom industry, where retaining existing customers is more cost-effective than acquiring new ones. This project focuses on predicting customer churn using machine learning techniques and identifying key factors that influence customer attrition.

🎯 Objective

To build and evaluate machine learning classification models that can accurately predict whether a customer will churn, and to analyze important features affecting churn behavior.

📂 Dataset

Source: Kaggle (Telecom Customer Churn Dataset)

Type: Secondary data

Contains customer demographic details, service usage information, and billing data.

Target Variable: Churn (Yes / No)

⚙️ Methodology
1. Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling using StandardScaler

Handling class imbalance using SMOTE

2. Exploratory Data Analysis (EDA)

Analysis of churn based on:

Contract type

Internet service

Monthly charges

Tenure

Visualization using bar charts and box plots

3. Model Building

The following models were implemented:

Logistic Regression

K-Nearest Neighbors (KNN)

Support Vector Classifier (SVC)

Decision Tree

Random Forest

XGBoost Classifier

4. Hyperparameter Tuning

GridSearchCV and RandomizedSearchCV were used to optimize model parameters

Overfitting was controlled by adjusting tree depth, regularization, and learning rates

5. Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

📈 Results

Among the tested models, XGBoost achieved the best overall performance.

Customers with month-to-month contracts and higher monthly charges showed a higher probability of churn.

Long-term contracts and bundled services were associated with lower churn rates.

🧠 Key Insights

Contract type is a strong predictor of churn.

Customers with fewer services are more likely to churn.

Proper handling of class imbalance significantly improves model performance.

Hyperparameter tuning helps reduce overfitting and improves generalization.

🛠 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Imbalanced-learn (SMOTE)


