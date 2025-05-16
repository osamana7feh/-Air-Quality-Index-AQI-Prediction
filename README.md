# Air Quality Index (AQI) Prediction with Machine Learning

This project uses machine learning to predict the Air Quality Index (AQI) based on pollutant levels collected from Indian cities. It covers full preprocessing, model training, evaluation, and deployment.

---

## Dataset
- Source: [Kaggle - Air Quality Data](https://www.kaggle.com/rohanrao/air-quality-data-in-india)
- Main file: `city_day.csv`

---

## Preprocessing Steps
- Handled missing values
- Dropped columns with high nulls (`Xylene`)
- Imputed missing values using column mean
- Split data into features and target (`AQI`)

---

## Models Used
- Linear Regression
- Random Forest
- XGBoost
- Gradient Boosting
- LightGBM
- Voting Regressor
- Stacking Regressor ✅ *(Best model)*

---

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Best model:
```text
Stacking Regressor
MAE: ~20.8
RMSE: ~39.7
R²: ~0.91
