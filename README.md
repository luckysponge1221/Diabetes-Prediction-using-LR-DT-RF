# Diabetes Prediction using Logistic Regression, Decision Tree, and Random Forest
This project explores the application of machine learning models to predict diabetes using a publicly available dataset from Kaggle. The aim was to evaluate and compare the performance of three algorithms — Logistic Regression (LR), Decision Tree (DT), and Random Forest (RF) — in terms of accuracy and AUC score, and to gain insights into handling biomedical data preprocessing and model evaluation.

## Project Structure
- `projek_siscer_diabetes.ipynb` — Main Jupyter Notebook with code, analysis, and results

## Project Overview
- **Data Preprocessing**  
  - Handled missing values by imputing the mean  
  - Removed outliers using IQR  
  - Checked and addressed class imbalances  

- **Models Implemented**  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  

- **Evaluation Metrics**  
  - Accuracy  
  - AUC (Area Under Curve)  

## Results
- Logistic Regression → Accuracy: **75%**, AUC: **0.83**  
- Decision Tree → Accuracy: **82%**, AUC: **0.82**  
- Random Forest → Accuracy: **85%**, AUC: **0.93**  

➡️ **Random Forest achieved the best overall performance.**

## Tech Stack
- Python  
- scikit-learn  
- pandas, numpy  
- matplotlib, seaborn

## References
Dataset: Kaggle - [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
scikit-learn Documentation: (https://scikit-learn.org/stable/)
