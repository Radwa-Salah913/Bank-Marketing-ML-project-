# Bank Marketing Analysis and Prediction

This project involves analyzing and building predictive models on the Bank Marketing dataset to gain insights into customer behavior and predict the likelihood of subscription to a term deposit. The dataset includes a mix of categorical and numerical features, allowing for a comprehensive exploration of marketing strategies.

## Dataset

Source:[Bank Marketing Dataset](https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing/data)

Dataset Description

Rows: 45,211
Columns: 17 (including the target variable y, which indicates if the client subscribed to a term deposit)

## Steps in the Project

## 1. Exploratory Data Analysis (EDA)

Analyzed the distribution of numerical features.

Visualized relationships between features using scatter plots, bar charts, and histograms.

Investigated correlations to identify important features influencing the target variable.

## 2. Data Preprocessing

Missing Values: Checked and imputed missing values where necessary.

Duplicates: Identified and removed duplicate records.

Encoding Categorical Data: Applied label encoding for binary categorical variables and one-hot encoding for multi-class variables.

Outlier Detection: Identified and treated outliers using statistical methods.

## 3. Feature Engineering

Analyzed correlation between features to remove multicollinearity.

Removed unnecessary or redundant columns to optimize model performance.

Scaled numerical features using Min-Max scaling.

## 4. Model Building

The following models were built and evaluated:

Naïve Bayes: Accuracy: 83%

Logistic Regression: Accuracy: 83%

Support Vector Machine (SVM): Accuracy: 83%

## 5. Model Evaluation

Compared model performance using metrics such as accuracy, precision, recall, and F1-score.

All three models achieved an accuracy of 83%, highlighting consistent performance across algorithms.
