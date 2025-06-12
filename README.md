# F1 Race Outcome Predictor

This project uses machine learning models to predict Formula 1 race results based on data pulled from the [FastF1 API](https://theoehrly.github.io/Fast-F1/). The code performs preprocessing, feature engineering, model training, and evaluation using multiple algorithms including XGBoost, LightGBM, CatBoost, and Neural Networks.

## 🚀 Features

- Uses race and qualifying data since 2018 via FastF1
- Custom feature engineering (e.g., GridPosDiff, TotalRaceTime)
- Handles missing data with penalty-based imputation
- Trains and compares multiple models (Random Forest, XGBoost, LightGBM, CatBoost, Neural Network)
- Evaluates models based on Mean Absolute Error and podium prediction accuracy

## 🛠 Installation

Before running, make sure you have Python 3.8 or higher installed.

Install dependencies:

```bash
pip install fastf1 pandas numpy scikit-learn tensorflow xgboost lightgbm catboost matplotlib
