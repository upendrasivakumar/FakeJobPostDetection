#🚀 Fake Job Post Detection

A machine learning project to detect fake job postings using NLP, EDA, and classification models.

🔗 Live Demo (Deployment): https://fake-job-post-detection-3.onrender.com

#📌 Project Overview

Online job portals contain both genuine and fraudulent listings. Fake postings often lead to scams or misuse of personal data.
This project uses Machine Learning to classify job posts as real or fake using text features and metadata.

#🎯 Objectives

Build an ML classification model for fake job detection

Perform EDA to identify fraud patterns

Apply text cleaning & TF-IDF vectorization

Train models:

Logistic Regression

Naive Bayes

Decision Tree

Random Forest

SVM

XGBoost

Compare performance and select the best model

Save model & vectorizer for deployment

#📊 Dataset

Size: 6,841 job postings × 18 features

Target: fraudulent (0 = real, 1 = fake)

Features:

Text: title, company_profile, description, requirements, benefits

Numeric: telecommuting, has_company_logo, has_questions, etc.

#⚙️ Steps Performed

Data cleaning & preprocessing

EDA (distribution plots, correlations, missing analysis)

TF-IDF feature engineering

Model training & evaluation

5-fold cross-validation

Hyperparameter tuning (GridSearchCV)

Deployment using the best model

#📈 Results

Best Model: Tuned XGBoost

Metrics: Highest F1-score & ROC-AUC

Example Predictions:

“Work from home, $5000/week, send bank details” → FAKE

“Infosys hiring Software Engineer via official portal” → REAL

#🛠️ Tech Stack

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

XGBoost

Deployment: Render

Visualizations: Confusion Matrix, ROC, Precision-Recall curves
