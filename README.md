# 🚢 Titanic Survival Prediction

A Machine Learning project that predicts whether a passenger survived the Titanic disaster using passenger information.

## 📌 Project Overview

This project uses the famous Titanic dataset from Kaggle to build a machine learning model for predicting passenger survival.

I implemented a complete Machine Learning workflow including:

- Data Loading
- Exploratory Data Analysis (EDA)
- Missing Value Handling
- Feature Engineering
- Categorical Encoding
- Train-Test Split
- Logistic Regression
- Random Forest Classification
- Model Evaluation
- Feature Importance
- Kaggle Submission

## 📊 Dataset

The dataset contains information about Titanic passengers, including:

- Passenger Class (`Pclass`)
- Sex
- Age
- Number of Siblings/Spouses (`SibSp`)
- Number of Parents/Children (`Parch`)
- Fare
- Port of Embarkation (`Embarked`)

The `Cabin` column was removed because it contained a large number of missing values.

## 🛠️ Feature Engineering

A new feature called `FamilySize` was created:

```python
FamilySize = SibSp + Parch + 1
