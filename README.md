Data Analysis Final Project
Irkutsk National Research Technical University · Baikal School of BRICS
Course: Data Analysis
Overview
This repository contains the final project for the Data Analysis master's course. It implements a complete statistical analysis pipeline for a biochemical marker dataset with a binary outcome, including exploratory analysis, correlation testing, binary logistic regression, PCA, and K-means clustering.
All code is written in base R with no external package dependencies, ensuring full reproducibility and compatibility.
Requirements
R ≥ 3.6.0
No additional packages required
Usage
Place the three input CSV files (distribution*.csv, factor_data*.csv, imputed_data*.csv) in the working directory.
Run the analysis script:
source("final_project_analysis.R")
All result tables and high-resolution figures will be generated automatically in analysis_results/.
Random seed is fixed to 20260620 for reproducible results.
Analysis Modules
Data preprocessing: missing value handling, outlier detection, skewness transformation, and standardization
Exploratory data analysis: descriptive statistics, distribution validation, normality tests
Correlation analysis: Pearson, Spearman, and point-biserial correlation with multiple testing correction
Logistic regression: univariate, factor-adjusted, and multivariate stepwise models with train-test validation
Principal component analysis: variance decomposition and biplot visualization
K-means clustering: optimal k selection and cluster outcome risk comparison
Author
Liu Yiran
June 2026
