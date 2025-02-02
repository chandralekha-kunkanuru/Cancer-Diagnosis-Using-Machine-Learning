# Cancer-Diagnosis-Using-Machine-Learning
Cancer Detection Using Machine Learning Algorithms
This repository contains code and analysis for detecting cancer using 
multiple machine learning algorithms. We compare the performance of 
Logistic Regression, Decision Tree, and Random Forest models. The project 
also includes essential data preprocessing steps to enhance model 
accuracy and reliability.
Dataset
The dataset (data.csv) contains various risk factors associated with 
breast cancer. It is used to train and evaluate machine learning models 
for cancer classification.
Project Structure
* data.csv – Dataset containing cancer-related features and labels.
* cancer_classifier.ipynb – Jupyter Notebook for data exploration, 
preprocessing, model training, and evaluation.
* README.md – This file, providing an overview of the project.
Preprocessing Steps
1. Feature Selection – Irrelevant and redundant features are removed to 
improve model performance.
2. Feature Scaling – Standardization is applied to ensure consistent 
scaling across all features.
Machine Learning Models
We implement and evaluate the following classification models:
1. Logistic Regression – A linear model used for binary classification 
based on probability estimation.
2. Decision Tree – A tree-based model that splits data based on feature 
values for decision-making.
3. Random Forest – An ensemble learning technique that combines multiple 
decision trees for higher accuracy and robustness.
Evaluation Metrics
To assess model performance, we use the following metrics:
* Accuracy – Overall correctness of predictions.
* Recall – Ability to correctly identify cancer-positive cases.
* Precision – Proportion of correctly predicted positive cases.
* F1-score – Harmonic mean of precision and recall, balancing both 
metrics.
