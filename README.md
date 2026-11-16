# CS 430 Assignment 3 – SLCM Classification

For this assignment, I used the SLCM rent arrears dataset to see if household and housing information could help predict which households have $3,000 or more in past-due rent.

I used five classification models: Logistic Regression, KNN, Decision Tree, Random Forest, and SVC. I compared their accuracy, recall, and F1 scores to see which model performed better.

## Files
- `CS430_Assignment3_SLCM_Classification.ipynb` – My notebook with the code, results, and explanations.
- `SLCM_rent_arrears_student_clean.csv` – The dataset used for this assignment.

## How to Run
Open the notebook in Jupyter Notebook or Google Colab and make sure the CSV file is uploaded or in the same folder. Run the cells in order to see the results.

## Results
I found that KNN had the highest F1 score and recall out of the five models. I also used GridSearchCV to test different settings for KNN and Random Forest.

This assignment helped me understand how different classification models work and why looking at recall and F1 is important instead of only accuracy.
