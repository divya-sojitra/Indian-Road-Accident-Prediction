# Accident Cause Prediction (Indian Roads Dataset)

## Overview

This repo performs **multi-class classification** on an Indian roads accident dataset to predict accident cause:
- `distraction`
- `overspeeding`
- `weather`
- `drunk driving`
- `poor road`

It includes:
- full pipeline in `accident_cause_prediction.ipynb`
- dataset in `indian_roads_dataset.csv`

---

## Project Structure

- `accident_cause_prediction.ipynb` — all-in-one tutorial with:
  - data loading
  - preprocessing
  - encoding
  - feature selection
  - train/test split
  - RandomForest training
  - evaluation + confusion matrix
  - SHAP-like feature importance
  - sample predictions + business insights
