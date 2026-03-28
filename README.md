# Student Performance Predictor

Predicting student exam scores using Machine Learning.

## Overview
Built an end-to-end ML pipeline to predict a student's average exam score
based on demographic and preparation factors.

## Dataset
[Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) — 1,000 student records with 5 features.

## Models Compared
| Model | RMSE | R² Score |
|---|---|---|
| Linear Regression | ~8.1 | ~0.21 |
| Decision Tree | ~6.4 | ~0.51 |
| **Random Forest** | **~4.2** | **~0.87** |

## Key Findings
- Test preparation course completion is the strongest predictor of performance
- Random Forest outperformed other models with 87% variance explained
- Parental education level showed moderate correlation with scores

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Google Colab

## How to Run
1. Open `student_performance.ipynb` in Google Colab
2. Upload `StudentsPerformance.csv` when prompted
3. Run all cells
