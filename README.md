
# Heart Disease Diagnosis

This machine learning project predicts whether a patient is at risk of developing heart disease based on clinical indicators. It uses the UCI Heart Disease dataset, which contains patient attributes such as age, blood pressure, cholesterol levels, and chest pain type.

The goal is to demonstrate how structured healthcare data and supervised machine learning can support early diagnosis and clinical decision-making.


## Contents

- `heart_disease_analysis.ipynb` – Jupyter notebook with steps to load, explore, preprocess and model the dataset.
- `heart.csv` –  The dataset contains 297 rows and 14 variables, including patient demographics (age, sex), clinical measurements (resting blood pressure, cholesterol, fasting blood sugar, etc.) and a diagnosis label indicating presence of heart disease.

## Steps to Run

1. Download `heart.csv` from Kaggle (see the Heart Disease Data dataset).  The CSV should include columns matching those described in the notebook (age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target).
2. Install required packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit‑learn`.
3. Open the notebook in Jupyter Notebook/Lab and run the cells sequentially.

## Extension Ideas

- Perform feature selection and hyperparameter tuning to optimise model performance.
- Use SHAP values or other interpretability techniques to understand risk factors.
- Explore the impact of balancing classes if the dataset is imbalanced.

This project highlights typical steps in a supervised classification workflow, showcasing data preprocessing, model training, evaluation and interpretation—valuable skills for healthcare analytics.

