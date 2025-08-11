 Elevate_Labs_Task_05

 Task 5 — Exploratory Data Analysis (EDA) 
# Overview
This project is part of my Data Analyst Internship Task 5, where the objective is to perform Exploratory Data Analysis (EDA) on the Titanic dataset to extract meaningful insights using visual and statistical exploration techniques.

# Objectives
- Load and understand the Titanic dataset.
- Explore data structure, missing values, and descriptive statistics.
- Perform univariate, bivariate, and multivariate analysis
- Visualize patterns, trends, and correlations.
- Summarize findings based on the analysis.

# Tools & Libraries
- Python
- Jupyter Notebook
-Libraries:
Pandas
NumPy
Matplotlib
Seaborn

# Dataset
File: train.csv from the Titanic dataset (Kaggle).

Contains information about Titanic passengers including demographics, ticket details, and survival status.

# EDA Process
- Data Loading & Inspection
- Used pd.read_csv() to load data.
- Checked dataset info, shape, and missing values.
- Univariate Analysis
- Count plots for survival, passenger class, and gender.
- Histogram for age distribution.
- Bivariate Analysis
- Survival by gender and class.
- Age vs Fare with survival status.
- Multivariate Analysis
- Correlation heatmap for numeric variables.
- Observations
- Added insights after each plot.

# Key Findings
Survival: More passengers died than survived.

Gender: Females had higher survival rates than males.

Class: 1st class passengers survived more often than 3rd class passengers.

Fare: Higher fares correlated with better survival chances.

Age: Age had less influence, but young children in high classes had higher survival.

Missing Data: Found in Age, Cabin, and Embarked.

# Project Files
Task5_EDA.ipynb → Jupyter Notebook with code, plots, and observations.

train.csv → Titanic dataset file.

Task5_EDA_Report.pdf → PDF version of the notebook.

README.md → Project description.
