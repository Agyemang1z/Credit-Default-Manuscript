# Enhancing Credit Default Prediction Using Boruta Feature Selection, DBSCAN, and Resampling Techniques

## Overview

This repository provides reproducible code and data for a credit default prediction study. The analysis focuses on class imbalance, feature selection, outlier detection, and ensemble learning for improved identification of default risk.

## Repository

- **Repository name:** `Credit-Default-Manuscript`
- **Repository type:** Jupyter Notebook research repository
- **Repository link:** https://github.com/Agyemang1z/Credit-Default-Manuscript
- **Primary author:** Edmund Fosu Agyemang
- **Academic identifier:** ORCID: https://orcid.org/0000-0001-8124-4493

## Repository Contents

The public repository listing identifies the following files:

- `Boruta.csv`
- `Borutta_DBSCAN.csv`
- `Credit_Default_Manuscript.ipynb`
- `README.md`
- `default of credit card clients.csv`

## Research Objectives

- Establish baseline model performance using the imbalanced credit default dataset.
- Apply Boruta feature selection to identify informative predictors.
- Use DBSCAN-based outlier detection to improve data quality.
- Compare class imbalance remedies including SMOTE, SMOTE-Tomek, and ADASYN.
- Evaluate traditional classifiers and advanced boosting algorithms for credit default prediction.

## Analytical Workflow

1. Load the credit default dataset and feature selection outputs.
2. Conduct preprocessing and define the binary default outcome.
3. Apply Boruta feature selection and DBSCAN-based outlier handling.
4. Train baseline models without resampling.
5. Apply class balancing methods and retrain models.
6. Compare models using F1 score, G-mean, ROC-AUC, and PR-AUC.

## Software Requirements

Recommended software and packages include:

- Python 3.10 or later
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- scikit-learn
- imbalanced-learn
- matplotlib
- xgboost
- lightgbm

## Reproducibility Guide

Run the project from a clean working directory. The following commands provide a suggested starting point:

```bash
git clone https://github.com/Agyemang1z/Credit-Default-Manuscript.git
cd Credit-Default-Manuscript
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install pandas numpy scikit-learn imbalanced-learn matplotlib xgboost lightgbm jupyter
jupyter notebook "Credit_Default_Manuscript.ipynb"
```

If file names include spaces, keep quotation marks around the file name when launching notebooks or scripts from the terminal.

## Expected Outputs

- Balanced and imbalance-aware model performance tables
- Feature selection outputs
- Outlier detection outputs
- Comparative classification metrics

## Data Availability and Responsible Use

The data and code are provided for scholarly, educational, and reproducibility purposes. Users should verify the original data source, data license, and any use restrictions before redistribution or secondary analysis. When the dataset contains human, health, financial, or election-related information, results should be interpreted responsibly and reported with appropriate methodological caution.

## Suggested Citation

Agyemang, E. F. (n.d.). *Enhancing Credit Default Prediction Using Boruta Feature Selection, DBSCAN, and Resampling Techniques* [Source code and data]. GitHub. https://github.com/Agyemang1z/Credit-Default-Manuscript

If this repository supports a manuscript, replace the citation above with the final article citation after publication. For stronger academic referencing, consider creating a GitHub release and archiving the release on Zenodo to obtain a DOI.


## Keywords

Credit default, Class imbalance, Boruta, DBSCAN, SMOTE, ADASYN, Gradient boosting

## Disclaimer

This repository is intended to support reproducible research. The code and outputs should not be used as a substitute for professional clinical, financial, legal, electoral, or policy judgment.
