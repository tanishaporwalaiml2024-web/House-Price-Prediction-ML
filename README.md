# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project predicts house prices using Machine Learning.

The project uses an India Housing Prices dataset and applies data preprocessing, categorical encoding, feature engineering, feature scaling, and Linear Regression to predict house prices.

The target variable is `Price_in_Lakhs`.

## 🎯 Objective

The objective of this project is to develop a Machine Learning model that can predict house prices based on different property-related features.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## 🤖 Machine Learning Algorithm

### Linear Regression

Linear Regression is used to predict the house price based on the available input features.

## 🔄 Project Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Categorical Encoding
5. Feature Engineering
6. One-Hot Encoding
7. Train-Test Split
8. Feature Scaling
9. Log Transformation
10. Model Training
11. Price Prediction
12. Model Evaluation

## 🧹 Data Preprocessing

The project includes:

- Missing-value checking
- Categorical variable encoding
- One-Hot Encoding
- Feature engineering
- Feature scaling using `StandardScaler`
- Log transformation using `log1p()`

## 🧠 Feature Engineering

Additional features were created during preprocessing, including:

- `total_score`
- `age`
- `PPS`
- `Square_PPS`

## 📊 Model Evaluation

The model is evaluated using R² Score.

Predictions are converted back from logarithmic scale using `expm1()`.

The exact evaluation results are available in the Jupyter Notebook.

## 📁 Project Structure

```text
House-Price-Prediction-ML/
│
├── House_Price_Prediction.ipynb
├── README.md
├── requirements.txt
│
└── dataset/
    ├── README.md
    └── india_housing_prices_sample.csv
