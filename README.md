# Iris Classification: Logistic Regression and Decision Trees

A cleaned and assignment-ready machine learning notebook for multiclass Iris classification.

## What is covered
- Exploratory data analysis with descriptive statistics and visualisations
- Data quality checks and target encoding
- Logistic Regression using One-vs-Rest, One-vs-One and Softmax approaches
- Decision Tree classification and hyperparameter tuning
- Class-weighted/balanced versions of all models
- Confusion matrices for baseline and balanced models
- Accuracy, precision, recall, F1-score, log loss and ROC-AUC
- Visual model comparison
- Discussion of findings and common data-leakage issues

The notebook supports common Iris CSV target names such as `species` and `Species`, and removes a standard `Id` column when present.

## Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/Iris_Classification_Analysis.ipynb
```

## Repository structure
```text
iris-classification-repository/
├── data/
│   └── Iris.csv
├── notebooks/
│   └── Iris_Classification_Analysis.ipynb
├── reports/
├── src/
├── .gitignore
├── README.md
└── requirements.txt
```
