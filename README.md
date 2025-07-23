# 🏡 Housing Price Predictor with Residual Learning and Ensemble Models

This project builds a machine learning pipeline to predict housing prices using ensemble models and residual learning. It utilizes Random Forest, Gradient Boosting, and XGBoost regressors, and further enhances accuracy with a two-stage residual correction model to reduce high-error predictions.

## 🚀 Features

- **Data Preprocessing & Feature Engineering**
  - Handles missing values, categorical encoding, and normalization.
  - Supports model-specific preprocessing for optimal performance.

- **Ensemble Models**
  - Trains and compares:  
    - Random Forest Regressor  
    - Gradient Boosting Regressor  
    - XGBoost Regressor  

- **Residual Learning**
  - Implements a two-stage prediction strategy:
    - Stage 1: Primary model prediction.
    - Stage 2: XGBoost trains on residual errors from stage 1 to refine results.

- **Visualization & Evaluation**
  - Residual plots for before and after correction.
  - Feature importance visualization.
  - RMSE and R² evaluation metrics.

## 📊 Technologies Used

- Python  
- Scikit-learn  
- XGBoost  
- NumPy & Pandas  
- Matplotlib & Seaborn  

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/tejasvarma-9/housing-price-predictor.git
   cd housing-price-predictor
