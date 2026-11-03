# Income Prediction Using Machine Learning

A Machine Learning project that predicts whether an individual's annual income is above or below $50K using the Adult Census Income dataset.

## Project Overview

This project focuses on analyzing demographic and employment-related data to understand income patterns and build a machine learning classification model.

The project follows a complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, hyperparameter tuning, and evaluation.

## Objectives

- Analyze the Adult Census Income dataset.
- Clean and preprocess raw data.
- Handle missing values and outliers.
- Perform Exploratory Data Analysis (EDA).
- Apply feature encoding and scaling techniques.
- Build and evaluate a machine learning classification model.
- Predict income categories based on input features.

## Dataset

**Adult Census Income Dataset**

The dataset contains demographic and employment-related information, including age, education, occupation, working hours, and other attributes.

**Target variable:** `income_binary`

- `0` – Income less than or equal to $50K
- `1` – Income greater than $50K

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Workflow

1. Data Collection and Loading
2. Data Cleaning and Preprocessing
3. Handling Missing Values
4. Outlier Detection using IQR
5. Exploratory Data Analysis
6. Feature Engineering
7. One-Hot Encoding
8. Feature Scaling using StandardScaler
9. Model Training using Gradient Boosting Classifier
10. Hyperparameter Tuning using GridSearchCV
11. Model Validation using StratifiedKFold
12. Model Evaluation

## Model Used

**Gradient Boosting Classifier**

The model was trained to classify individuals into income categories. Stratified cross-validation and GridSearchCV were used for model validation and hyperparameter tuning.

**Reported Accuracy: Approximately 80%**

Refer to the Jupyter Notebook for the exact evaluation results.

## Key Learnings

- Practical experience with data preprocessing and analysis.
- Understanding of machine learning classification techniques.
- Feature engineering and model optimization.
- Model evaluation and performance analysis.
- Working with Python data science libraries.

## Future Enhancements

- Compare multiple machine learning algorithms.
- Improve model performance through further tuning.
- Develop a web-based income prediction application.
- Add model explainability and visualization.

## Author

**Yangyaseni Sahoo**

MCA Graduate | AI/ML Enthusiast

## Project Repository

[View Income Prediction Using Machine Learning on GitHub](https://github.com/yangyaseni2001/Income_Prediction_Using_Machine_Learning)

---

*This project was developed as part of an academic machine learning capstone project.*