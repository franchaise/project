# ANOMALY-ENHANCED STACKED ENSEMBLE FOR CREDIT CARD FRAUD DETECTION

## Project Overview
The purpose of this project is to improve the efficiency in detection of fraudulent credit card transactions by integrating anomaly detection techniques with predictive modeling. The approach combines unsupervised anomaly detection technique with and supervised learning models such as Logistic regression, Gradientboost classifier and XGBoost classifier.

## Motivation
Credit card fraud is a significant problem that causes substantial financial losses globally. This project seeks to enhance fraud detection methods by combining the strengths of anomaly detection and predictive modeling to create a more robust solution.

## Dataset
- **Description**: The project uses anonymized dataset from Open ML. The dataset is a two-day credit card transaction dataset obtained from European credit card users consummated in 2013. It consists of 284,807 legitimate and fraudulent transactions. The dataset is highly imbalanced with the fraud component only 492 transactions. It is an estimated 64MB in size and collected in arff format. The dataset has 31 features with 28 of the features (V1 to V28) anonymized through principal component analysis (PCA) for data protection purposes. Other features include Amount, Time and Class
- **Preprocessing**: The data imbalance was handled using SMOTE.

## Methodology
- **Anomaly Detection**: LOF model was used to identify fraudulent transactions. The anomaly score from this was then added to the hybrid model 
- **Predictive Modeling**: Supervised algorithms (as Logistic regression, XGBoost Classifier and GradientBoost Classifier) were trained using the stacking approach
- **Evaluation Metrics**: Precision, recall, F1-score were used to evaluate model performance.


## Results
The model achieved a Precision score of 0.97, a Recall score of 0.80 and an F1- score of 0.88.


# project
