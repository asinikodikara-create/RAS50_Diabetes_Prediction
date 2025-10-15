Project summary: This repository contains a complete workflow for predicting diabetes risk using a national health survey dataset (BRFSS 2023). The analysis includes data cleaning, exploratory data analysis (EDA), feature selection, target mapping, model training and evaluation, and explainability and explanation stability analysis. The main notebook is exported as a python file with all code and results.

Repo contents:

Diabetes_Prediction.ipynb — python file (code + outputs, visualizations, tables).
diabetes_prediction.csv — intermediate CSV created by reading the supplied .xpt data source (generated early in the notebook).
selected_diabetes_features.csv — CSV with the selected 23 variables (renamed for readability).
cleaned_diabetes_dataset.csv — cleaned dataset after mapping the target and dropping rows with invalid/ignored responses (shape reduced from 433,323 → 332,475 rows).
stability_*.csv / sex_notable_delta_ranks.csv – explainability and explanation stability artifacts (feature importance, SHAP comparisons).
stability_*.png – visual summaries of model stability and top-feature consistency.
