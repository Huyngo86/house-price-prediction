# House Price Prediction

This project studies supervised regression on the Ames housing data. The supplied notebook explores data inspection, missing-value handling, feature scaling, one-hot encoding, and regression with linear, Ridge, and Lasso models, including polynomial features.

## Notebook

`[Code]-Project-5.1-House-Price-Prediction-Advanced-Regression-Techniques.ipynb` loads the training data from:

```text
/content/train-house-prices-advanced-regression-techniques.csv
```

Download the Ames competition data separately and update the path for your environment. The data is not included here.

## Results

The CV reports 1,460 records, a 173-feature dataset, comparison of six regression algorithms, and LightGBM as the best model with **RMSE 0.1249**, **MAE 0.0839**, and **R² 0.9058**.

The supplied notebook currently contains Linear Regression, Ridge, Lasso, and polynomial-feature experiments. It does not implement LightGBM or reproduce the CV's normalized RMSE/MAE figures, so the CV results are listed as reported results rather than results verified from this notebook.

