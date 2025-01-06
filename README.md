# MLM Project 2

## Overview
This repository contains the implementation and analysis for **MLM Project 2**, focused on machine learning models for classification and regression. The project involves data preprocessing, feature engineering, and model evaluation to identify patterns and clusters in trade-related datasets.

## Features
- **Data Preprocessing**: Handling missing data, encoding categorical variables, and scaling numerical features.
- **Exploratory Data Analysis (EDA)**: Insights into the dataset, key variables, and their thresholds.
- **Supervised Machine Learning**: Implementation of models such as Logistic Regression, SVM, Decision Tree, Random Forest, KNN, Naive Bayes, and SGD.
- **Model Evaluation**: Comparative analysis of accuracy, precision, recall, and runtime across models.
- **Feature Importance**: Identification of significant variables influencing classification.

## Project Workflow
1. **Data Preprocessing**:
   - Handled missing values (none detected in this dataset).
   - Categorical encoding using ordinal encoding.
   - Min-Max scaling for numerical features.

2. **Exploratory Data Analysis**:
   - Analyzed key features such as `Country`, `Product`, `Quantity`, `Value`, `Weight`, and more.
   - Visualized thresholds and outliers.

3. **Model Implementation**:
   - Logistic Regression
   - Support Vector Machine (SVM)
   - Stochastic Gradient Descent (SGD)
   - Decision Tree
   - K-Nearest Neighbors (KNN)
   - Random Forest
   - Naive Bayes

4. **Model Evaluation**:
   - Performed cross-validation and test set evaluations.
   - Compared runtime, memory usage, and classification metrics.

5. **Feature Analysis**:
   - Identified significant features for better classification.

## Key Findings
- Logistic Regression performed best in terms of runtime but struggled with imbalanced datasets.
- Random Forest provided robust handling of non-linear relationships but required higher memory and runtime.
- SVM and SGD performed similarly, focusing heavily on specific clusters while failing for others.
- Decision Trees offered interpretability but were prone to overfitting.

-Ashish Michael Chauhan (055007)
