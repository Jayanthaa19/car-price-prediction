# Used Car Price Prediction

A machine learning coursework project exploring the factors associated with used-car prices using Python and regression techniques.

## Overview

This notebook covers exploratory data analysis, data cleaning, feature engineering, model training, hyperparameter tuning and model evaluation.

## Techniques and tools

- **Data analysis:** Pandas, NumPy
- **Visualisation:** Matplotlib, Seaborn
- **Preprocessing:** Scikit-learn pipelines, categorical encoding and feature scaling
- **Models:** K-Nearest Neighbours, Decision Tree, Linear Regression and Ridge Regression
- **Evaluation:** Train/test split, cross-validation, grid search, R², MAE and MSE

## Project files

- `car_price_prediction.ipynb` — coursework code (saved outputs removed)
- `requirements.txt` — Python dependencies
- `.gitignore` — excludes local and private files from routine Git tracking

## Dataset availability

The original vehicle adverts dataset was supplied by Auto Trader for academic coursework. Permission to redistribute it publicly has not been established, so **the dataset is not included**.

The notebook expects a file named `adverts.csv` in the project directory. An appropriately authorised dataset with the expected columns is required to run it. The repository is intended to demonstrate the analysis and modelling approach; the published notebook alone is **not independently reproducible**.

Saved notebook outputs were removed to avoid publishing rows or results derived from the supplied dataset.

## Running the notebook (with authorised access to the dataset)

1. Install Python and Jupyter Notebook or JupyterLab.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Place your authorised `adverts.csv` in the same directory as the notebook.
4. Open `car_price_prediction.ipynb` and run the cells in sequence.

The notebook reflects the original coursework and has not been re-executed or validated against a replacement dataset.

## Notes

This is an academic portfolio project. No affiliation with or endorsement by Auto Trader is implied.
