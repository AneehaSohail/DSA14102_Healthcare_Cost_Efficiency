## DSAI 4103 — Business Analytics Project

### Project Overview
Predicts Medicare hospital spending scores and segments hospitals into 
Low/Medium/High risk categories using machine learning.

### Dataset
- Medicare Hospital Spending Per Patient (Hospital-level)
- Medicare Hospital Spending Per Patient (State-level)  
- Medicare Spending Per Beneficiary (Detailed)

Source: CMS Medicare Data

### Files
- DSAI4103_Project.ipynb — Main analysis notebook
- hospital_cost_model.pkl — Trained ML model
- Medicare_Hospital_*.csv — Dataset files

### How to Run
1. Install requirements: pip install pandas numpy scikit-learn shap seaborn matplotlib
2. Open the .ipynb file in Jupyter Notebook
3. Run all cells in order

### Key Findings
High hospital costs are driven primarily by geographic location (state/county).
Model: Random Forest / Gradient Boosting ensemble comparison with SHAP explainability.

