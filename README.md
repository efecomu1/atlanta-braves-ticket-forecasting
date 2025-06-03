# Atlanta Braves Ticket Demand Forecasting

An XGBoost-based forecasting model developed in the Sports Analytics course at Emory University to project ticket demand at the game level.

## 📌 Objective
Forecast game-level ticket demand using historical sales, team schedule, opponent quality, day-of-week, and playoff odds to support strategic pricing and promotion.

## 🧠 Methodology
- Feature Engineering: Rolling averages, encoded categorical variables
- Train/Val/Test split: 2018–2022 training, 2023 validation, 2024 forecast
- Model: XGBoost Regressor

## 📊 Model Performance (2023)
- RMSE: 2525.74
- MAE: 1946.14

## 🛠️ Tools & Tech
- Python (XGBoost, pandas, sklearn)
- Matplotlib, Seaborn for visualization

## 📄 Files
- `notebooks/demand_forecasting_assignment.ipynb`: Full modeling pipeline
- `report/`: Written business summary of insights
