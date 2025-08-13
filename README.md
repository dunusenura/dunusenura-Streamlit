# 🍷 Wine Quality Prediction with Machine Learning

This project is a Streamlit web application that allows users to explore and analyze the Wine Quality Dataset. It provides interactive visualizations and prediction functionalities related to wine quality.

## Features

- Interactive data visualization
- Exploratory data analysis (EDA) of wine quality attributes
- Predict wine quality based on input features
- User-friendly web interface built with Streamlit

## Dataset

The dataset used is the popular https://dunusenura-app-gbatvoav8rlctwwi8mibpk.streamlit.app from the UCI Machine Learning Repository.


### Features:
- `fixed acidity`
- `volatile acidity`
- `citric acid`
- `residual sugar`
- `chlorides`
- `free sulfur dioxide`
- `total sulfur dioxide`
- `density`
- `pH`
- `sulphates`
- `alcohol`
- `quality` (target variable)

---

## 🛠️ Project Workflow

### 1. Data Loading & EDA
- Load dataset using Pandas.
- Check for missing values, outliers, and feature distributions.
- Explore relationships between features and target variable.

### 2. Data Preprocessing
- Handle missing values (if any).
- Feature scaling (StandardScaler).
- Optional: Encode categorical features (not needed for this dataset).

### 3. Model Training
- Train at least two models (e.g., Logistic Regression, Random Forest, Gradient Boosting).
- Compare performance using cross-validation.
- Select the best model based on accuracy/F1-score.

### 4. Model Saving
- Save the trained pipeline using `joblib`:
```python
import joblib
joblib.dump(model, "model.pkl")


