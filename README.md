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

## Key improvements over the original notebook
- Replaced the machine-specific dataset path with a repository-relative path.
- Prevented data leakage by splitting before fitting the scaler.
- Completed the previously unfinished EDA assignment.
- Completed the class-weighting assignment for all requested models.
- Added confusion-matrix visualisations.
- Added structured metric comparison and explanations.
- Added reproducible documentation and repository structure.

## Dataset
Place the `Iris.csv` dataset used for the assignment in:

`data/Iris.csv`

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
│   ├── Iris_Analysis_Original.ipynb
│   └── Iris_Classification_Analysis.ipynb
├── reports/
├── src/
├── .gitignore
├── README.md
└── requirements.txt
```

## Note
The dataset file was not included in the uploaded notebook, so final numeric outputs are generated when `Iris.csv` is added to `data/`. No results have been fabricated.
