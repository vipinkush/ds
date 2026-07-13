# CodeAlpha_UnemploymentAnalysis

## Task 2: Unemployment Analysis with Python — CodeAlpha Data Science Internship

### 📌 Overview
This project analyzes unemployment rate data across Indian states (2019–2020),
with a focus on the impact of COVID-19 on unemployment trends. It covers data
cleaning, exploratory data analysis, visualization, and policy-relevant insights.

### 📊 Datasets
- `data/Unemployment_in_India.xlsx` — State-wise unemployment data with Rural/Urban split
- `data/Unemployment_Rate_upto_11_2020.xlsx` — State-wise unemployment data with zone and geo-coordinates

### 🔍 What the notebook covers
1. Data loading & inspection
2. Data cleaning (whitespace, missing rows, date parsing, merging datasets)
3. Descriptive statistics
4. National unemployment trend over time
5. COVID-19 impact analysis (pre vs during/post lockdown)
6. Rural vs Urban impact comparison
7. State-wise unemployment comparison (overall & lockdown peak)
8. Zone-wise comparison
9. Seasonal pattern analysis
10. Labour participation rate vs unemployment relationship
11. Correlation analysis
12. Key insights & policy recommendations

### 🛠 Tools & Libraries
- Python
- Pandas — data cleaning & manipulation
- Matplotlib & Seaborn — data visualization
- Jupyter Notebook

### 📁 Project Structure
```
├── Unemployment_Analysis_India.ipynb   # Main analysis notebook (fully executed)
├── data/
│   ├── Unemployment_in_India.xlsx
│   └── Unemployment_Rate_upto_11_2020.xlsx
├── images/                              # Exported chart images
└── README.md
```

### ▶️ How to run
```bash
pip install pandas numpy matplotlib seaborn jupyter openpyxl
jupyter notebook Unemployment_Analysis_India.ipynb
```

### 📈 Key Findings
- Unemployment rate rose sharply during the March–May 2020 COVID-19 lockdown compared to pre-COVID levels.
- Urban areas saw a steeper unemployment increase than rural areas during the lockdown.
- Unemployment impact varied significantly across states and zones.
- Some seasonal variation in unemployment exists outside the pandemic period.

### 🎓 Internship
This project was completed as part of the **CodeAlpha Data Science Internship** (Task 2).

---
*Internship by [CodeAlpha](https://www.codealpha.tech)*
