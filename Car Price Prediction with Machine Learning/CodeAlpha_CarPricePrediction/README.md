# CodeAlpha_CarPricePrediction

## Task 3: Car Price Prediction with Machine Learning — CodeAlpha Data Science Internship

###  Overview
This project builds and compares regression models to predict the **selling price of a
used car** based on features like manufacturing year, ex-showroom price, kilometers
driven, fuel type, seller type, transmission, and ownership history.

###  Dataset
- `data/car_data.xlsx` — 301 used car listings, 9 columns
  (`Car_Name`, `Year`, `Selling_Price`, `Present_Price`, `Driven_kms`, `Fuel_Type`,
  `Selling_type`, `Transmission`, `Owner`)

###  What the notebook covers
1. Data loading & inspection
2. Data cleaning & feature engineering (`Car_Age`, `Brand`)
3. Exploratory data analysis (distributions, relationships, boxplots by category, correlation)
4. Preprocessing pipeline (scaling + one-hot encoding via `ColumnTransformer`)
5. Model training & comparison: Linear Regression, Decision Tree, Random Forest
6. Evaluation: MAE, RMSE, R², 5-fold cross-validation
7. Predicted vs. actual price plot
8. Feature importance analysis
9. Example prediction on a new/sample car
10. Key insights

###  Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib & Seaborn — visualization
- Scikit-learn — preprocessing, regression models, evaluation
- Jupyter Notebook

###  Project Structure
```
├── Car_Price_Prediction.ipynb   # Main analysis & modeling notebook (fully executed)
├── data/
│   └── car_data.xlsx
├── images/                       # Exported chart images
└── README.md
```

###  How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter openpyxl
jupyter notebook Car_Price_Prediction.ipynb
```

###  Key Findings
- **Present (ex-showroom) price** is the strongest predictor of resale value.
- **Car age** has a strong negative relationship with price (depreciation).
- **Kilometers driven** has a moderate negative effect on price.
- **Random Forest** outperformed Linear Regression and a single Decision Tree, capturing
  non-linear depreciation patterns.

###  Internship
This project was completed as part of the **CodeAlpha Data Science Internship** (Task 3).

---
*Internship by [CodeAlpha](https://www.codealpha.tech)*
