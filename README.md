# Machine Learning: Wine Quality Prediction and Customer Segmentation

Two data science analyses completed as part of a Machine Learning coursework assignment.

## Overview

This repository presents two distinct machine learning workflows:

1. **Wine quality prediction:** examine wine characteristics and model wine quality using supervised regression.
2. **Online retail customer segmentation:** use Recency, Frequency, and Monetary (RFM) features to identify customer groups through unsupervised clustering.

## Methods

### Wine quality prediction
- Exploratory analysis using histograms, boxplots and correlation heatmaps
- Data preparation, outlier analysis and feature scaling
- Regression model development, including linear regression and decision trees
- Evaluation using MAE, RMSE and R²

### Customer segmentation
- RFM feature engineering from retail transactions
- K-Means clustering with elbow and silhouette analysis
- Hierarchical clustering using Ward linkage
- Interpretation of clusters using feature distributions and visualisations

## Technology

Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn and Jupyter Notebook.

## Notebook

The original coursework notebook is intended to be placed at `notebooks/machine_learning_assignment.ipynb`. It includes saved visualisations and results where available.

## Data availability and reproducibility

The original coursework datasets are not bundled in this repository. The notebook documents the analysis and saved outputs, but **cannot necessarily be run end-to-end without the original CSV files**. No replacement data or experimental results have been fabricated.

See [DATA_AVAILABILITY.md](DATA_AVAILABILITY.md) for further notes.

## Portfolio context

This is a historical coursework project, presented to demonstrate machine learning fundamentals, methodological choices, exploratory analysis and interpretation. It is not claimed to be a production ML application.
