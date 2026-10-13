# Heavy Equipment Selling Price Prediction

## 📌 Overview

This project focuses on predicting the selling prices of heavy equipment using historical auction data and machine learning regression techniques.

The goal is to develop predictive models that estimate equipment auction prices by analyzing relevant features, applying data preprocessing and feature engineering, and comparing different regression algorithms.

---

## 🎯 Objectives

- Perform data cleaning and exploratory data analysis (EDA)
- Identify and handle missing values and categorical features
- Analyze price distributions and relationships between features
- Apply data preprocessing and feature engineering techniques
- Build and compare machine learning regression models
- Evaluate model performance using Root Mean Squared Logarithmic Error (RMSLE)
- Improve predictive performance through hyperparameter tuning

---

## 📊 Dataset Description

The project uses historical heavy equipment auction data to predict selling prices.

The analysis focuses on:

- **Numerical Features:** Numerical attributes describing the equipment and its characteristics
- **Categorical Features:** Categorical attributes requiring appropriate encoding
- **Target Variable:** Equipment selling price

The dataset is examined to understand missing values, feature distributions, and patterns that may influence auction prices.

*Note: Update this section with the exact dataset name, target column, and feature examples used in your notebook.*

---

## 🔍 Exploratory Data Analysis (EDA)

### Key Areas of Analysis

- Examined missing values across the dataset
- Investigated categorical features and their distributions
- Analyzed heavy equipment price distributions
- Explored patterns and relationships in the historical auction data
- Identified preprocessing requirements for regression modelling

---

## 🛠️ Data Preprocessing

The following techniques were used to prepare the data for modelling:

- Missing-value treatment
- Categorical feature encoding
- Numerical transformations
- Feature engineering
- Preparation of training data for regression models

These steps helped prepare the dataset for consistent model training and evaluation.

---

## 🤖 Model Building

Multiple tree-based gradient boosting regression models were developed and compared.

### Models Used

- **XGBoost Regressor:** Gradient boosting model for predicting equipment selling prices
- **LightGBM Regressor:** Efficient gradient boosting approach for tabular data
- **CatBoost Regressor:** Gradient boosting model designed to handle categorical data effectively

Model configurations were tuned to improve predictive performance.

---

## 📈 Evaluation Metrics

The models were evaluated using **Root Mean Squared Logarithmic Error (RMSLE)**.

- **Best reported RMSLE:** 0.19766

A lower RMSLE indicates better predictive performance, with the metric evaluating differences between logarithmic transformations of actual and predicted prices.

---

## 🔧 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- Matplotlib / Seaborn (if used in the notebook)

---

## 📂 Project Structure

```text
heavy-equipment-selling-price-prediction/
├── heavy_equipment_selling_price_prediction.ipynb
└── README.md
```

*Adjust the notebook filename and project structure to match your repository.*

---

## 🚀 Future Improvements

- Explore additional feature engineering techniques
- Conduct systematic hyperparameter optimization
- Compare model performance using cross-validation
- Analyze prediction errors across different price ranges
- Investigate additional regression algorithms and ensemble approaches

---

## 🙌 Conclusion

This project demonstrates the application of machine learning regression techniques to heavy equipment auction price prediction. Through exploratory data analysis, data preprocessing, feature engineering, model comparison, and hyperparameter tuning, the project explores how historical auction data can be used to estimate equipment selling prices.

The best reported model configuration achieved an RMSLE of **0.19766**, demonstrating the potential of gradient boosting models for this prediction task.
