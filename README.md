# CODESOFT-Credit-Card-Fraud-Detection

Name: KOMAL YADAV
Internship/Company Name: CODESOFT

**Abstract**
Credit card fraud detection is a critical problem in the financial sector. This project uses machine learning techniques to identify fraudulent transactions in a dataset of credit card activity. By preprocessing the data, handling class imbalance, and evaluating classification models, we aim to build a robust system capable of distinguishing between genuine and fraudulent transactions.

**Objective**
To develop a machine learning model capable of detecting fraudulent credit card transactions. The goal is to assist financial institutions in identifying and preventing fraud in real time, minimizing financial losses.

**Dataset Description**
The dataset was sourced from Kaggle and contains European cardholder transactions from September 2013. It includes 284,807 records and 31 features: 28 anonymized principal components (V1–V28), Time, Amount, and Class. The target column Class has values 0 (genuine) and 1 (fraud).

**Methodology**
Data Preprocessing
Normalized the Amount feature using StandardScaler.

Dropped the Time column as it was not needed.

Confirmed there were no missing values.

Exploratory Data Analysis (EDA)
Explored the class distribution showing high imbalance (very few fraud cases).

Visualized the class imbalance with count plots.

Analyzed feature correlations to understand relationships.

Feature Selection
Used all 30 features (after preprocessing) for model training, as these were principal components optimized for variance.

Models Used
Logistic Regression

Random Forest Classifier

Evaluation Metrics
Precision

Recall

F1-score

ROC-AUC score

Confusion matrix visualization

**Results**
The Random Forest model outperformed Logistic Regression, achieving an F1-score above 0.90 and an ROC-AUC score above 0.97.
Applying SMOTE oversampling balanced the dataset, improving recall and detection of fraudulent transactions.

**Conclusion**
This project demonstrates that machine learning models can effectively detect credit card fraud. Handling class imbalance with SMOTE and comparing different classifiers enhances model performance and reliability. For future work, real-time detection, cost-sensitive learning approaches, and deployment as an API are recommended.

**References**
Kaggle Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Scikit-learn Documentation

imbalanced-learn SMOTE Tutorials



