# Accident Cause Prediction (Indian Roads Dataset)

## Overview

This repo performs **multi-class classification** on an Indian roads accident dataset to predict accident cause:
- `distraction`
- `overspeeding`
- `weather`
- `drunk driving`
- `poor road`

It includes:
- full pipeline in `complete_tutorial.py`
- model-only script in `accident_cause_prediction.py`
- explanation-only script in `detailed_explanation.py`
- dataset in `indian_roads_dataset.csv`

---

## Project Structure

- `complete_tutorial.py` — all-in-one tutorial with:
  - data loading
  - preprocessing
  - encoding
  - feature selection
  - train/test split
  - RandomForest training
  - evaluation + confusion matrix
  - SHAP-like feature importance
  - sample predictions + business insights
- `accident_cause_prediction.py` — concise model code (production-ready)
- `detailed_explanation.py` — concept walkthrough (no model execution)
- `indian_roads_dataset.csv` — 20k accident entries
- `requirements.txt` — dependency list
- `README.md` — this file
- `ML_CONCEPTS.md` — key ML terminology & methodology

---

## Setup

1. Clone repository
2. Create virtual env (recommended)

```bash
python3 -m venv .venv
source .venv/bin/activate
