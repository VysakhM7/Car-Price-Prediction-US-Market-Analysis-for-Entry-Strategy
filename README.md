# Car Price Prediction: US Market Analysis

This project uses regression models to understand what factors affect car prices in the American market. It's designed to help a Chinese car manufacturer plan entry into the US market.

## Contents
- Data Preprocessing
- Model Training (Linear, Tree-based, SVR)
- Model Comparison
- Feature Importance
- Hyperparameter Tuning
- Business Insights

## Best Model
**Random Forest Regressor** with tuned parameters:
- R² Score: 0.91
- Key Factors: Engine size, Horsepower, Car width, Brand, Curb weight

## Dataset
Provided: `CarPrice_Assignment.csv` (source: [dataset link](your-dataset-link))

## How to Run
1. Clone the repo
2. Run `car_price_prediction.ipynb` in Jupyter

---
- Random Forest was the best model with R² = 0.91 after tuning.
- Key factors affecting price: engine size, horsepower, car width, curb weight, and brand.
- Strategy: Focus on performance and size specs, and align with brand perception in the US.
