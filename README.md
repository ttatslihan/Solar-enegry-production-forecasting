# Machine Learning-Based Forecasting & Optimization for Renewable Energy

Predicting next-day solar power generation using weather and 
production data, to help power plant managers reduce energy 
imbalance costs and improve production planning.

## Problem
Solar power output is highly variable and hard to predict, 
which creates costly energy imbalances for plant operators. 
This project builds forecasting models to predict next-day 
solar generation with higher accuracy.

## Approach
- **Data collection:** Pulled weather and production data via 
  APIs (EPİAŞ & Meteostat)
- **Preprocessing:** Cleaned, merged, and engineered features 
  from weather variables
- **Modeling:** Built and compared three approaches:
  - Artificial Neural Network (ANN)
  - Random Forest (RF)
  - Long Short-Term Memory (LSTM)
- **Evaluation:** Compared models on [RMSE, MAE, R2 etc.]

## Results
- Random Forest performed best with MAE of 17%

## Tech Stack
Python · pandas · scikit-learn · TensorFlow/Keras · 
Matplotlib · API integration

## What this demonstrates
End-to-end data science workflow: from raw API data to 
deployed forecasting models with business impact.
