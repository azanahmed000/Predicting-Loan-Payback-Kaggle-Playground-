# Loan Payback Prediction

This project was built for a Kaggle Playground competition.  
The goal is to predict whether a borrower will pay back a loan using a synthetic tabular dataset.

---

## Approach

- Preprocessed the data by dropping ID, aligning train/test feature columns, and applying one-hot encoding  
- Trained multiple tree-based models:
  - Random Forest  
  - XGBoost  
  - LightGBM  
- Evaluated models using ROC-AUC on a validation split

---

## Results

- **LightGBM:** 0.91868 AUC  
- **Random Forest:** 0.91212 AUC  
- Other models stayed near the 0.90 range

Because the dataset is synthetic, the performance naturally plateaus around this level.

---

## Dataset

Kaggle Playground dataset link:  
**[(http://kaggle.com/competitions/playground-series-s5e11)]**

---

## Files

- `notebook.ipynb` — preprocessing + model training workflow  
- `submission.csv` — final Kaggle submission  
- Dataset files available on the Kaggle competition page

---

## Notes

This is a practice project focused on clean workflow, model comparison, and generating proper Kaggle submissions on large synthetic datasets.
