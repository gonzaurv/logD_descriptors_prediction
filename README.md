# Lipophilicity Prediction of Sulfonyl Compounds

This repository contains Python scripts for lipophilicity prediction of fluorinated and non-fluorinated sulfonil compounds using descriptors, DFT, and topological features. The scripts include modules for data processing, feature extraction, model training, evaluation, and Jupyter notebooks for documentation.

## Introduction

The provided code allows users to reproduce and conduct multilinear regression analysis as described in "REFERENCE PAPER" . The analysis focuses on predicting the lipophilicity (LogP) of sulfonil compounds utilizing various features and descriptors.

## Authors and Original Paper

This work is based on the research conducted by "NOMBRES and was published in "Journal". The reference to the original paper is as follows:

"DOI"

## Getting Started

To use this code, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the necessary dependencies installed (see `requirements.txt`).
3. Run the provided Python scripts or Jupyter notebooks.

## Analysis Workflow

The main steps of the analysis include:

1. **Data Preparation**: Load and preprocess the dataset containing descriptors for the sulfonil compounds.
2. **Linear Regression Analysis**: Perform multilinear regression analysis for all possible combinations of the dataset features to predict LogP values.
3. **Correlation Analysis**: Calculate the correlation matrix and visualize it using a heatmap to identify correlated features.

## Linear Regression Analysis

The linear regression analysis is conducted using the provided Python script (`linear_regression_analysis.py`). This script performs multilinear regression for all possible combinations of features in the dataset to predict LogP values. Results are saved in Excel format for further analysis.

## Correlation Analysis

The correlation analysis is conducted using the provided Python script (`correlation_analysis.py`). This script calculates the correlation matrix of the dataset features and visualizes it using a heatmap to identify correlated features. Results are saved in Excel format for further analysis.

## Results

The results of both the linear regression analysis and correlation analysis are saved in Excel files (`scores_withA0-B0_2024_CORREGIDO.xlsx` and `Correlacion_scores_18_2024.xlsx`, respectively) within the repository.

---
