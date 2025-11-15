# 🚜 Bulldozer Price Prediction

This repository contains a machine learning project for predicting the sale price of used bulldozers using historical auction data.

The core logic and experiments are in the notebook:

- `bulldozer_price_prediction.ipynb` (your current notebook)

The project is inspired by the **Blue Book for Bulldozers** regression challenge (Kaggle).

## 🎯 Objective
Predict the future sale price of a bulldozer given its characteristics such as:
- Model ID
- Usage hours
- Year of manufacture
- Product size
- Enclosure type
- And other auction-related features

## 🧠 What this project includes
- Data loading and cleaning
- Feature engineering (dates, categorical encoding, etc.)
- Train/validation split
- Model training (e.g., RandomForestRegressor / other regressors)
- Evaluation using RMSE / MAE
- Visualizations of predictions vs actual prices

## ▶️ How to Run

1. **Create and activate a virtual environment** (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter and open the notebook**:
```bash
jupyter notebook bulldozer_price_prediction.ipynb
```

4. Run the notebook cells step by step.

## 📂 Recommended Project Structure

You can structure your repo like this:

```text
.
├── bulldozer_price_prediction.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
└── data/
    ├── Train.csv
    ├── Valid.csv
    └── Test.csv
```

> Note: `data/` is usually not committed to Git (already ignored in `.gitignore`).

## 📊 Dataset

You can use the **Blue Book for Bulldozers** dataset from Kaggle (or your own cleaned version) and place CSVs inside the `data/` directory.

## 📝 Next Ideas to Improve
- Try advanced models (XGBoost, LightGBM, CatBoost)
- Hyperparameter tuning
- Proper time-based validation split
- Model saving/loading with `joblib` or `pickle`

## 📜 License
This project is licensed under the MIT License. See `LICENSE` file for details.
