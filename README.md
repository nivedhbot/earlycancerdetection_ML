# Early Cancer Detection Machine Learning

This repository contains Jupyter notebooks and data files used for building
Bayesian Network models to predict breast and lung cancer.

## Contents
- `BreastCancer.ipynb` – Notebook for analyzing the Wisconsin Breast Cancer dataset and training a Bayesian Network using `pgmpy`.
- `LungCancer.ipynb` – Notebook for modeling lung cancer risk factors and building a Bayesian Network classifier.
- `breast-cancer-wisconsin-data.csv` – Dataset containing features extracted from digitized images of breast masses.
- `survey lung cancer.csv` – Survey dataset with features related to lung cancer risk.
- `sweet_report_lungcancer.html` – Exploratory data report generated for the lung cancer dataset.

## Usage
Open the notebooks in Jupyter to run the analyses. Both notebooks expect the datasets to be present in the same directory as the notebooks. The lung cancer notebook has been updated to load the dataset using a relative path:

```python
import pandas as pd

df_lung = pd.read_csv("survey lung cancer.csv", encoding="utf-8")
```

The notebooks demonstrate how to load the datasets, perform basic exploration, and train Bayesian Network models for prediction.

