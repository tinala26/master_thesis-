# master_thesis-

# ASD Classification & Explainability Pipeline

This repository contains my Master's thesis project focused on building an interpretable machine learning pipeline for Autism Spectrum Disorder (ASD) classification using clinical and demographic data.

##  Features
- Preprocessing of questionnaire and demographic data
- Multiple classifiers: Logistic Regression, Random Forest, Decision Tree, XGBoost, TabNet, and a custom LTCN model
- Data imbalance handling using SMOTE
- Feature importance and explainability using SHAP, LIME, PMC, SOFI, and permutation methods
- Fairness evaluation by gender
- Robustness testing with noisy training data
- Visualization: Confusion matrices, ROC, Precision-Recall curves, flip curves, and more

## Technologies
Python, scikit-learn, XGBoost, PyTorch TabNet, SHAP, LIME, SMOTE, Matplotlib, Seaborn

## File
- `asd_pipeline.py`: Full training, evaluation, and explainability pipeline

## Results
All plots and model performance summaries are saved to `results/` directory.


