# 🏠 House Prices – Advanced Regression Techniques
This repository contains my solution for the Kaggle competition: House Prices – Advanced Regression Techniques. The challenge involves predicting the final price of homes based on various features such as square footage, location, and neighborhood attributes.

- 📊 Goal: Predict final home prices using various features.
- 💡 Techniques used: EDA, feature engineering, regression models.
- 🛠️ Created in a Kaggle notebook environment.

## Table of contents
- [Overview](#overview)
- [Approach](#approach)
- [Results](#results)
- [Dataset ](#dataset )
- [What I Learned](#what-i-learned)
- [Note](#note)  
## 📌 Overview
The goal of this project is to develop a machine learning model that accurately predicts home sale prices. This competition is an excellent opportunity to practice regression techniques, feature engineering, and model evaluation.

## 🔍 Approach
### 1. 🧼 Data Preprocessing
- Handled missing values using domain knowledge and imputation techniques.
- Transformed categorical features using label encoding and one-hot encoding.
- Applied log transformation to skewed numerical features.
### 2. 📊 Feature Engineering
- Combined correlated features.
- Created new features (e.g., total square footage, age of house).
- Removed outliers based on domain-specific thresholds.
### 3. 🤖 Model Training
- Random Forest
### 4. 📈 Evaluation
- Optimized for MDI (Mean Decrease in impurity).
- Selected final model based on validation performance.

## 📈 Results
- The features "GrLivArea", "GarageArea", '1stFleSF", "TotRmsAbvGrd" and "YearRemodAdd" are found to be highly correlated to my target feature . 
- For my model I got MDI = 0.
- Best Public Score in kaggle till now for this project: [Score: 0.18851].

Final model used: [Random Forest]

## 📥 Dataset 
The dataset is not included in this repository due to Kaggle’s terms of use.

🔗 You can download the dataset from the competition page.

## 📚 What I Learned
- Practical application of regression models in real-world data.
- Importance of data preprocessing and domain knowledge in feature engineering.

## Note 
- Skewness of SalePrice: 1.88 but sometimes I get '- 0.18', that is why I did not modify the target variable while training as well as testing the model.
