# CodeAlpha_SalesPrediction

## Task 4: Sales Prediction using Python — CodeAlpha Data Science Internship

### 📌 Overview
This project predicts product **sales** based on advertising spend across three
platforms — **TV, Radio, and Newspaper** — and analyzes how changes in advertising
budget impact sales outcomes, to deliver actionable marketing insights.

### 📊 Dataset
- `data/Advertising.xlsx` — 200 records: advertising spend (in $ thousands) on TV,
  Radio and Newspaper, and resulting Sales (in thousands of units).

### 🔍 What the notebook covers
1. Data loading & inspection
2. Data cleaning (dropping the redundant index column, duplicate check)
3. Exploratory data analysis (distributions, spend-vs-sales scatter plots, correlation, pairplot)
4. Advertising budget mix (share of spend by channel)
5. Preprocessing & train/test split
6. Model training & comparison: Linear Regression, Ridge Regression, Decision Tree, Random Forest
7. Evaluation: MAE, RMSE, R², 5-fold cross-validation
8. Predicted vs. actual sales plot
9. Channel impact analysis (linear coefficients + Random Forest feature importance)
10. What-if simulation: predicted sales as spend increases per channel
11. Example prediction for a new advertising budget
12. Key insights & marketing recommendations

### 🛠 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib & Seaborn — visualization
- Scikit-learn — preprocessing, regression models, evaluation
- Jupyter Notebook

### 📁 Project Structure
```
├── Sales_Prediction.ipynb   # Main analysis & modeling notebook (fully executed)
├── data/
│   └── Advertising.xlsx
├── images/                   # Exported chart images
└── README.md
```

### ▶️ How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter openpyxl
jupyter notebook Sales_Prediction.ipynb
```

### 📈 Key Findings
- **TV advertising is the dominant driver of sales** — highest correlation, largest
  linear coefficient, and highest feature importance.
- **Radio advertising has a real, secondary positive effect** on sales.
- **Newspaper advertising shows the weakest relationship with sales**, contributing
  little incremental predictive value once TV and Radio are accounted for.
- Linear Regression already performs strongly, since the advertising–sales
  relationship in this dataset is close to linear.

### 🎓 Internship
This project was completed as part of the **CodeAlpha Data Science Internship** (Task 4).

---
*Internship by [CodeAlpha](https://www.codealpha.tech)*
