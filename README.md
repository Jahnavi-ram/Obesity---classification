# Obesity-classification

## Overview
This project aims to classify obesity levels based on various features like BMI, age, weight, etc. The project compares the performance of different machine learning models including Logistic Regression, Random Forest, Gradient Boosting, XGBoost, and SVM.

## Dataset 

The dataset used in this project is related to obesity levels based on personal attributes and habits. It contains multiple features such as:

- BMI
- Weight
- Height
- Age
- Family History with Overweight
- Eating Habits (e.g., frequency of consumption of vegetables, fast food)
- Physical Activity Levels

This dataset is publicly available and can be found [here](https://www.kaggle.com/datasets/jpkochar/obesity-risk-dataset).

## Model Performance

The following machine learning models were evaluated for obesity classification:

- **Logistic Regression**: Accuracy = 0.85
- **Random Forest**: Accuracy = 0.91
- **Gradient Boosting**: Accuracy = 0.90
- **XGBoost**: Accuracy = 0.91
- **SVM**: Accuracy = 0.87

Random Forest and XGBoost provided the best overall performance based on metrics like accuracy, precision, recall, F1-score, and AUC.

## Results and Visualizations

This project includes a comprehensive analysis using the following visualizations:

- **Confusion Matrices** for each model to evaluate classification performance.
- **Feature Importance** plot from Random Forest to identify the most influential features.
- **Precision-Recall Curves** to evaluate the precision and recall trade-offs for each model.
- **ROC-AUC Curves** for comparing the receiver operating characteristic across models.
- **Distribution Plots** for features like Age, Height, Weight, and other relevant attributes to understand data characteristics.
- **Box Plots** showing distributions of Age and BMI across different Obesity Levels.
- **Heatmaps** displaying correlations between various features.
- **Model Comparison** bar charts for Accuracy, Precision, Recall, and F1-Score.

## Dependencies
- Python 3.x
- Pandas
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn
