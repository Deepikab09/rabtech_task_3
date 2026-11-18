# Task 03 â€“ Feature Engineering & Preprocessing Pipeline

## Files
- `Task_03_Feature_Engineering_Preprocessing.ipynb` â€“ complete Jupyter Notebook implementation.
- `credit_risk_sample.csv` â€“ sample tabular credit-risk dataset used by the notebook.
- `requirements.txt` â€“ required Python packages.

## Run
1. Download all three files into the same folder.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter Notebook, JupyterLab, or Google Colab.
4. Run all cells from top to bottom.

## What is implemented?
- Train/test split before transformations.
- Numerical imputation and scaling.
- Categorical imputation and one-hot encoding.
- Reusable `ColumnTransformer` and Scikit-learn `Pipeline`.
- Random Forest classification and evaluation.
- Feature ranking using tree-based importance and mutual information.
- Numerical correlation analysis.

## Dataset note
The included CSV is a synthetic educational sample, not real financial/customer data. Do not use its predictions for real credit decisions.
