# Boston_housing
This repository contains a machine learning project based on the **Boston Housing dataset**. It includes data exploration, data analysis, and the training and evaluation a basic models to predict housing prices.  

Access the HTML version of the Jupyter notebook [here](https://maelwennlbdr.github.io/Boston_housing/).  


## Summary of the project
- **Environment Setup**: Creating a new conda environment with necessary packages (`numpy`, `pandas`, `scikit-learn`, and `ydata-profiling`).
- **Loading the Boston Housing Dataset**: Loading the Boston housing dataset using an older version of `scikit-learn`.
- **Data Exploration**: Generating a profiling report to explore the dataset’s columns and key statistics.
- **Correlation Analysis**: Analyzing the correlation between features and the target variable `MEDV` (median house value) using a heatmap.
- **Linear Regression (One Feature)**: Building a simple linear regression model using the `RM` feature to predict `MEDV`.
- **Linear Regression (Multiple Features)**: Building another regression model using `RM`, `LSTAT`, and `INDUS` features to improve predictions.
- **Model Comparison**: Comparing the performance of both models using MSE and R² scores. Generating graphs to visualize predictions versus true values.

