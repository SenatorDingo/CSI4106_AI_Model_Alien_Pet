# Phase 2: Machine Learning Pipeline

## Objective
Build and compare supervised learning models on the cleaned Alien Pet Health dataset.

## Workflow

- Constructed a train/test split with stratification
- Applied preprocessing pipeline:
  - Numeric scaling
  - Categorical one-hot encoding
- Trained baseline classical models (e.g., Logistic Regression, KNN, Decision Tree, Random Forest)
- Compared models using classification metrics (accuracy, F1, precision, recall)
- Performed hyperparameter tuning and cross-validation
- Selected a primary model based on generalization and stability

## Missing-Data Experiment

- Evaluated the missing-data version of the dataset
- Applied practical imputation strategies for numeric and categorical features
- Measured impact on model quality relative to clean-data baseline

## Outcome
A robust classical ML baseline was established, with clear evidence on model ranking and expected performance trade-offs under imperfect data conditions.
