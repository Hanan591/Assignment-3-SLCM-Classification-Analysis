# CS 430 Assignment 3 — SLCM Classification

This individual notebook compares Logistic Regression, KNN, Decision Tree, Random Forest, and SVC to predict `high_arrears` (past-due rent of $3,000 or more) from de-identified household and housing information.

## Files
- `CS430_Assignment3_SLCM_Classification.ipynb`: notebook with questions, code, results, and discussion.
- `SLCM_rent_arrears_student_clean.csv`: provided course dataset.

## Run
Open the notebook in Jupyter or Colab, keep the CSV in the same working folder, and run all cells in order. Requires pandas, matplotlib, scikit-learn, and IPython. All models use the same stratified 80/20 split (random_state=42). Missing values and encoding are handled inside training pipelines. GridSearchCV uses 3-fold CV on training data only.

