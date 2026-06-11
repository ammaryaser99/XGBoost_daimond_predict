# Diamond Price Prediction with XGBoost

A machine learning notebook for predicting diamond prices from tabular features using XGBoost. The repository includes the training and test datasets, a Jupyter notebook workflow, and a sample submission file.

## Project Goal

Build a regression model that estimates diamond prices from structured attributes such as cut, color, clarity, carat, and related measurements.

## Repository Contents

| File | Purpose |
|---|---|
| `diemond_predict.ipynb` | Main exploratory analysis and modeling notebook |
| `train.csv` | Training dataset |
| `test.csv` | Test dataset |
| `sample_submission.csv` | Example submission format |

## Typical Workflow

1. Load and inspect the diamond dataset.
2. Clean and encode categorical features.
3. Train an XGBoost regression model.
4. Evaluate model performance.
5. Generate predictions for the test dataset.

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- scikit-learn
- XGBoost

## How to Run

```bash
pip install pandas scikit-learn xgboost notebook
jupyter notebook diemond_predict.ipynb
```

## Notes

The notebook file name is kept as-is for compatibility with the existing repository history. A future cleanup could rename it to `diamond_price_prediction.ipynb`.
