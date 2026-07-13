# CodeAlpha_IrisClassification

## Task 1: Iris Flower Classification — CodeAlpha Data Science Internship

### 📌 Overview
This project trains machine learning models to classify Iris flowers into one of
three species — *Iris-setosa*, *Iris-versicolor*, or *Iris-virginica* — based on
four measurements: sepal length, sepal width, petal length, and petal width.

### 📊 Dataset
- `data/Iris.csv` — 150 samples, 50 per species, with `Id`, 4 numeric measurement
  columns, and a `Species` label.

### 🔍 What the notebook covers
1. Data loading & inspection
2. Data cleaning (dropping the `Id` column, duplicate check)
3. Exploratory data analysis (boxplots by species, pairplot, correlation heatmap, petal scatter plot)
4. Preprocessing (label encoding target, scaling features, stratified train/test split)
5. Model training & comparison: Logistic Regression, KNN, Decision Tree, Random Forest, SVM
6. Evaluation: accuracy, 5-fold cross-validation, classification report, confusion matrix
7. Feature importance analysis
8. Example prediction for a new flower
9. Key insights

### 🛠 Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib & Seaborn — visualization
- Scikit-learn — preprocessing, classification models, evaluation
- Jupyter Notebook

### 📁 Project Structure
```
├── Iris_Classification.ipynb   # Main analysis & modeling notebook (fully executed)
├── data/
│   └── Iris.csv
├── images/                      # Exported chart images
└── README.md
```

### ▶️ How to run
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Iris_Classification.ipynb
```

### 📈 Key Findings
- **Petal length and petal width are far more discriminative** than sepal
  measurements for distinguishing species.
- ***Iris-setosa* is perfectly separable** from the other two species.
- **SVM and Random Forest achieved the highest test accuracy (96.7%)**, with all
  models scoring above 93%, since the classes are well-separated in this dataset.
- Some overlap exists between *Iris-versicolor* and *Iris-virginica*, the main
  source of any misclassifications.

### 🎓 Internship
This project was completed as part of the **CodeAlpha Data Science Internship** (Task 1).

---
*Internship by [CodeAlpha](https://www.codealpha.tech)*
