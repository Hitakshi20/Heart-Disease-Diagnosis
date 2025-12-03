
# Heart Disease Diagnosis

This project analyses the **Heart Disease** dataset (available on Kaggle) containing 14 variables (e.g., age, sex, chest pain type, blood pressure, cholesterol) for 297 patients.  The data can be used to predict whether a patient has heart disease based on their clinical measurements and demographics.

## Contents

- `heart_disease_analysis.ipynb` – Jupyter notebook with steps to load, explore, preprocess and model the dataset.
- `heart.csv` –  Please download the heart disease dataset from Kaggle and place it in this directory before running the notebook.

## Steps to Run

1. Download `heart.csv` from Kaggle (see the Heart Disease Data dataset).  The CSV should include columns matching those described in the notebook (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target).
2. Install required packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit‑learn`.
3. Open the notebook in Jupyter Notebook/Lab and run the cells sequentially.

## Extension Ideas

- Perform feature selection and hyperparameter tuning to optimise model performance.
- Use SHAP values or other interpretability techniques to understand risk factors.
- Explore the impact of balancing classes if the dataset is imbalanced.

This project highlights typical steps in a supervised classification workflow, showcasing data preprocessing, model training, evaluation and interpretation—valuable skills for healthcare analytics.

