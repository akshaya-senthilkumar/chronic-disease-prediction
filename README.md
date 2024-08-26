
# Chronic Disease Prediction

This project utilizes machine learning techniques to predict chronic diseases based on patient data. The goal is to provide early warnings and help in managing health risks.
## Dataset

The dataset used for this project is publicly available and can be accessed [here](https://www.kaggle.com/datasets/abhia1999/chronic-kidney-disease). The dataset includes various features relevant to chronic diseases.
## Preprocessing Steps

The data preprocessing involved the following steps:

1. Assigning Feature Names: We assigned appropriate names to the dataset columns for clarity.

2. Converting Data Types: Ensured that the data types were suitable for analysis and modeling.

3. Handling Missing Values: Imputed or removed missing values to ensure data quality.

4. Feature Encoding: Applied encoding techniques to handle categorical variables.

5. Correlation Analysis: Identified correlations between features to understand relationships and inform feature selection.

6. Splitting Data: Divided the dataset into training and testing sets for model validation.
## Feature Engineering

We performed feature encoding to convert categorical variables into a format suitable for machine learning models. The correlation analysis helped in understanding the relationships between features.
## Modeling

We used the following machine learning classifiers:

- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest
- Decision Tree

These models were trained on the processed data and evaluated using various performance metrics.
## Evaluation

The models were evaluated using metrics such as accuracy, precision, recall, and F1-score. The results from these metrics helped in comparing the effectiveness of each classifier in predicting chronic diseases.
## Conclusion

This project provides insights into predicting chronic diseases using various classifiers. Each model's performance can guide further research and model optimization.