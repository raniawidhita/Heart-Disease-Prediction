# Heart-Disease-Prediction

This repository contains the **Heart Disease Dataset** obtained from Kaggle: [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
The goal of this project is to explore, analyze, and build predictive insights about factors associated with heart disease using structured medical data.

---

## Overview

Heart disease remains one of the leading causes of death worldwide.  
Understanding the patterns, correlations, and factors contributing to heart disease can help in early detection and prevention.

This repository provides:

- A clean and organized version of the dataset  
- Exploratory Data Analysis (EDA)  
- Statistical summaries  
- Visualizations  
- Preprocessing scripts for ML pipelines  
- Documentation for further model development  

---

**Columns include:**
- age
- sex
- cp (chest pain type)
- trestbps (resting blood pressure)
- chol (cholesterol)
- fbs (fasting blood sugar)
- restecg
- thalach
- exang
- oldpeak
- slope
- ca
- thal
- target (0 = no disease, 1 = disease)

---

## Data Preparation
Steps performed to clean and prepare the dataset:

**Missing Values** Checking and handling missing data.

**Duplicate Values** Identifying and removing duplicate entries.

**Outliers** Detecting outliers using methods such as boxplot, Z-score, or IQR.

**Imbalanced Data** Inspecting target label distribution; applying SMOTE or undersampling when needed.

**Feature Encoding** Transforming categorical features into numerical form using Label Encoding or One-Hot Encoding.

---

## Exploratory Data Analysis (EDA)
Initial analysis to understand the structure and patterns of the dataset:

**Data Types** Identifying nominal, ordinal, and numerical features.

**Mean, Median, Mode** Explaining when each central tendency measure is appropriate.

**Five Number Summary** Includes: minimum, Q1, median, Q3, maximum.

**Data Distribution** Using histograms, density plots, pairplots, and other distribution visualizations.

**Visualization** Correlation heatmaps, bar plots, box plots, scatter plots, and additional supporting visualizations.

---

## Feature Engineering
Enhancing the dataset by:
- Adding new features  
- Transforming existing features  
- Applying normalization or standardization when required  

---

## Data Training
Splitting the dataset into:
- Training set  
- Testing set  

Used for training and evaluating models.

---

## Machine Learning Modeling
Modeling process includes:

**Cross Validation** Ensuring model stability and reducing overfitting.

**Hyperparameter Tuning** Optimizing model parameters using GridSearchCV or RandomizedSearchCV.

**Model Exploration** Testing various algorithms such as Logistic Regression, Random Forest, SVM, KNN, etc.

**Learning Curves** Analyzing model performance based on the amount of training data.

---

## Model Evaluation
Evaluating model performance using metrics such as:
- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  

---

## Prediction
Using the trained model to make predictions on new, unseen data.

---


