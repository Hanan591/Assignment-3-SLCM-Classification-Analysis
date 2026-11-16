# CS 430 Assignment 3 — SLCM Classification

This individual notebook compares Logistic Regression, KNN, Decision Tree, Random Forest, and SVC to predict `high_arrears` (past-due rent of $3,000 or more) from de-identified household and housing information.

## Files
- `CS430_Assignment3_SLCM_Classification.ipynb`: notebook with questions, code, results, and discussion.
- `SLCM_rent_arrears_student_clean.csv`: provided course dataset.

## Run
Open the notebook in Jupyter or Colab, keep the CSV in the same working folder, and run all cells in order. Requires pandas, matplotlib, scikit-learn, and IPython. All models use the same stratified 80/20 split (random_state=42). Missing values and encoding are handled inside training pipelines. GridSearchCV uses 3-fold CV on training data only.

## Responsible use and AI assistance
Data are de-identified; do not try to identify households. Predictions are not causal evidence and must not determine assistance eligibility on their own. AI assistance was used to draft code and explanations; the student must verify the analysis, understand the results, and disclose assistance as required by the course.
