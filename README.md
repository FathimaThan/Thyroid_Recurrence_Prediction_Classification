# Thyroid Recurrence Prediction

This project aims to predict the recurrence of thyroid conditions using machine learning algorithms. The dataset contains various features related to patients' medical history, treatments, and demographics.

## Dataset Description

The dataset used in this project is sourced from Kaggle and includes the following columns:

- Age: Age of the patient
- Gender: Gender of the patient
- Smoking: Smoking status
- Hx Smoking: History of smoking
- Hx Radiotherapy: History of radiotherapy treatment
- Thyroid Function: Thyroid function status
- Physical Examination: Physical examination findings
- Adenopathy: Presence of adenopathy
- Pathology: Pathology findings
- Focality: Focality of the condition
- Risk: Risk assessment
- T: Tumor classification
- N: Nodal classification
- M: Metastasis classification
- Stage: Cancer stage
- Response: Response to treatment
- Recurred: Recurrence status

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/jainaru/thyroid-disease-data/data).

## Project Overview

1. **Data Preprocessing**: The dataset underwent preprocessing steps to ensure data quality and prepare it for modeling. Duplicates were identified and removed from the dataset. Although there were no missing values or outliers detected, categorical variables were encoded for modeling purposes.

2. **Exploratory Data Analysis (EDA)**: Visualizations were created to understand the distribution of features, identify patterns, and explore relationships between variables.

3. **Model Building**: Various machine learning models, including XGBoost, Random Forest, and Logistic Regression, were trained and evaluated to predict thyroid recurrence.

4. **Model Evaluation**: The models were evaluated using metrics such as accuracy, precision, recall, and F1-score to determine the best-performing algorithm.

## Conclusion

The Random Forest model demonstrated the best performance in predicting thyroid recurrence, achieving an accuracy of 97%. Further improvements can be made by refining feature engineering and exploring advanced modeling techniques.
