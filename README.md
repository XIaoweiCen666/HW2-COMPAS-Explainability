# HW2 - Explaining the COMPAS Replacement Model

## Purpose of the Analysis
This project was completed for Individual Homework 2 in DNSC 6330. The goal is to build and explain a COMPAS replacement model in Python. The notebook trains a model to predict whether a defendant receives a high or low COMPAS score, then uses explainability methods to understand both global and individual model behavior.

The analysis includes:
- model training with logistic regression and gradient-boosted trees
- subgroup performance comparison by race
- SHAP summary and waterfall explanations
- LIME explanations for selected individuals
- counterfactual explanations using DiCE
- a short governance discussion about the strengths and limitations of these methods

## Python Libraries Used
The main Python libraries used in this project are:

- pandas
- numpy
- scikit-learn
- matplotlib
- shap
- lime
- dice-ml

## Files in This Repository
- `HW2_.ipynb` — the main Jupyter Notebook implementing the full workflow
- `README.md` — project overview and reproduction instructions

