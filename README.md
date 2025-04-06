# 💎 Diamond Price Prediction
A machine learning project to predict the price of diamonds based on their physical characteristics such as carat, cut, color, clarity, and more.
<img src="https://github.com/goldstring/diamond_price_prediction_using_machine_learning_regression/blob/main/2151695032.jpg?raw=true" />
---

## 📊 Project Overview

The aim of this project is to build a regression model that can accurately predict diamond prices using features like:

- Carat weight
- Cut quality
- Color grade
- Clarity grade
- Physical dimensions (depth, table, x, y, z)

---

## 🧠 Model Pipeline

1. **Data Collection** – Kaggle Diamond Dataset
2. **Data Cleaning & EDA** – Handled missing values, outliers, and performed visualization
3. **Feature Engineering** – Label encoding, scaling, and polynomial features
4. **Model Selection** – Tried multiple regression algorithms:
   - Linear Regression
   - Ridge/Lasso Regression
   - Random Forest Regressor
   - XGBoost Regressor
5. **Evaluation** – Based on MAE, RMSE, and R² Score
6. **Model Deployment** – Final model saved as `models/model.pkl` for deployment

---



## 📈 Results

- ✅ Best Model: `Random Forest Regressor`
- ✅ R² Score on Test Set: `0.98+`
- ✅ MAE: `~300`
- ✅ RMSE: `~500`

---

## 🚀 How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/diamond-price-prediction.git
   cd diamond-price-prediction
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run Jupyter Notebook or Python script:
   ```bash
   jupyter notebook
   ```

---

## 📦 Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib / seaborn
- xgboost
- joblib

---

## 🧾 License

This project is licensed under the [MIT License](LICENSE).

---


