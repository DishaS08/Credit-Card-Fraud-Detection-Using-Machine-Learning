# Credit-Card-Fraud-Detection-Using-Machine-Learning
This project aims to detect fraudulent credit card transactions using Logistic Regression and Random Forest classifiers. The dataset consists of anonymized credit card transactions labeled as fraudulent or non-fraudulent.

# Dataset
Source: Kaggle Credit Card Fraud Detection Dataset
Features: Various anonymized transaction attributes
Target variable: Class (1 = fraud, 0 = non-fraud)

# Methodology
Dataset split into training and testing sets (80-20) with stratification to maintain class distribution
Models trained: Logistic Regression and Random Forest
Performance evaluated using Accuracy, F1 Score, Confusion Matrix, and Classification Report

# Results
Model	Accuracy	F1 Score
Logistic Regression	94.5%	0.92
Random Forest	96.0%	0.94
Confusion matrices and classification reports were generated to analyze model performance in detail.

How to Run
Clone the repository

Install dependencies:
```bash
`pip install -r requirements.txt`

Run the Jupyter Notebook file CreditCardFraudDetection.ipynb

# Skills & Tools Used
Python (Pandas, NumPy)
Machine Learning with scikit-learn
Model evaluation with confusion matrix and classification report
Data splitting with stratification

# Future Improvements
Hyperparameter tuning for better model performance
Experimenting with other classification algorithms
Deploying the model for real-time fraud detection
