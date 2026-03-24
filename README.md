# Student Stress Level Classification

This mini project for Artificial Intelligence (CS 481) predicts whether a student has low or high academic stress using supervised machine learning.

## Project Goal
- Build a binary classification model from the Student Stress dataset.
- Convert the original stress score into:
  - 0: Low Stress
  - 1: High Stress

## Dataset
- File: student_stress.csv
- Records include academic and behavioral factors such as peer pressure, academic pressure at home, study environment, coping strategy, bad habits, academic competition rate, and semester.

## Workflow
1. Data loading and dataset overview
2. Data cleaning and preprocessing
   - Missing value check
   - Duplicate removal
   - Target conversion to binary stress_level
   - Removal of unnecessary date fields
3. Exploratory data analysis with class distribution and feature relationship visuals
4. Feature selection
5. Train/test split (80/20)
6. Feature scaling with StandardScaler
7. Model training with three algorithms:
   - Logistic Regression
   - Decision Tree
   - Random Forest
8. Model evaluation and comparison using accuracy
9. Confusion matrix for the selected best model
10. Feature importance analysis using Random Forest

## Result Summary
- The notebook compares all three models and selects the best one based on test accuracy.
- Results are presented with a comparison table, confusion matrix, and feature-importance plot.

## Files
- student_stress_project.ipynb: Full analysis and modeling pipeline
- student_stress.csv: Dataset used in this project

## How to Run
1. Open student_stress_project.ipynb in Jupyter Notebook or VS Code.
2. Run all cells from top to bottom.
3. Review outputs, metrics, and final conclusion.
