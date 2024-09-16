# Titanic Dataset - Predicting Survival

This repository contains code and analysis for predicting the survival of passengers aboard the Titanic. The goal is to build a model that accurately predicts whether a passenger survived based on various features such as age, gender, class, etc.

## Steps performed in the Jupyter Notebook:

1. **Data Loading**: Loaded the Titanic dataset using pandas.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzed missing values.
   - Visualized data distributions and relationships using seaborn and matplotlib.
   - Explored relationships between survival and key features.
3. **Data Preprocessing**:
   - Imputed missing values (for columns like Age and Embarked).
   - Converted categorical variables into numerical using one-hot encoding.
   - Scaled the features to prepare for model training.
4. **Model Selection**:
   - Tried various models including Logistic Regression, Decision Trees, and Random Forest.
   - Tuned hyperparameters using GridSearchCV.
5. **Model Evaluation**:
   - Evaluated models using accuracy, precision, recall, and F1-score.
   - Compared performance across different models and selected the best one.
6. **Conclusion**:
   - Finalized the best model and made predictions on the test dataset.

## Requirements:
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
