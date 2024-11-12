# Lipophilicity Prediction of Sulfonyl Compounds

This repository contains Python scripts for lipophilicity prediction of fluorinated and non-fluorinated sulfonil compounds using descriptors, DFT, and topological features. The scripts include modules for data processing, feature extraction, model training, evaluation, and Jupyter notebooks for documentation.

## Introduction

### Why Statistical Analysis First?
Before diving into advanced machine learning algorithms, it’s crucial to understand the underlying relationships and trends within your data. Statistical analysis, particularly with simpler models like linear regression, allows us to evaluate dependencies and correlations between variables, making it easier to interpret patterns and trends. Sometimes, these straightforward models provide valuable insights into system behavior that would otherwise remain hidden, ultimately guiding better decision-making and model selection.

### What Does This Tool Do?
This script automates the process of fitting multiple linear regression models using single variables and pairs of variables as predictors for the target variable. For each combination:

It computes important metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), model intercept, and coefficients.
It evaluates the predictive power (R-squared) for each model to help you assess how well each variable or pair of variables explains the variability in your target variable.
Through this approach, you can identify which individual or paired features contribute most to your model’s performance, giving you a solid understanding of how each feature interacts with your target variable.

### Key Benefits
**Fast Exploration:** Quickly assesses the impact of each feature (alone or in pairs) on the target variable.
**Error Metrics:** Provides critical metrics that help in understanding each model’s performance.
**System Trends:** Aids in identifying feature importance and directional trends within your dataset.
In short, this tool allows you to efficiently gauge the predictive power of your data’s features, helping you understand your data better and establish a foundation for further analysis.

The provided code allows users to reproduce and conduct multilinear regression analysis as described in "REFERENCE PAPER" . The analysis focuses on predicting the lipophilicity (logD) of sulfonil compounds utilizing various features and descriptors.

## Authors and Original Paper

This work is based on the research conducted by "NOMBRES and was published in "Journal". The reference to the original paper is as follows:

"DOI"

## Getting Started

Before using this code, it's important to set up a Python environment on your PC with all the necessary packages and libraries installed. Follow these steps to get started:

1. Clone this repository to your local machine.
2. Create a virtual environment using a tool like `virtualenv` or `conda`. This will help isolate your project's dependencies from other projects.

    ```bash
    # Using virtualenv
    virtualenv venv
    source venv/bin/activate  # Activate the virtual environment
    
    # Using conda
    conda create --name myenv
    conda activate myenv
    ```

3. Install the required dependencies listed in the `requirements.txt` file using `pip` or `conda`.

    ```bash
    pip install -r requirements.txt
    ```

   or

    ```bash
    conda install --file requirements.txt
    ```

4. Once the environment is set up and dependencies are installed, you can run the provided Python scripts or Jupyter notebooks for data analysis and model training.

---


## Analysis Workflow

The main steps of the analysis include:

1. **Data Preparation**: Load and preprocess the dataset containing descriptors for the sulfonil compounds.
2. **Linear Regression Analysis**: Perform multilinear regression analysis for all possible combinations of the dataset features to predict logD values.
3. **Correlation Analysis**: Calculate the correlation matrix and visualize it using a heatmap to identify correlated features.

## Linear Regression Analysis

The linear regression analysis is conducted using the provided Python script (`linear_regression_analysis.py`). This script performs multilinear regression for all possible combinations of features in the dataset to predict logD values. Results are saved in Excel format for further analysis.

## Correlation Analysis

The correlation analysis is conducted using the provided Python script (`correlation_analysis.py`). This script calculates the correlation matrix of the dataset features and visualizes it using a heatmap to identify correlated features. Results are saved in Excel format for further analysis.

## Results

The results of both the linear regression analysis and correlation analysis are saved in Excel files (`scores_withA0-B0_2024_CORREGIDO.xlsx` and `Correlacion_scores_18_2024.xlsx`, respectively) within the repository.

---
