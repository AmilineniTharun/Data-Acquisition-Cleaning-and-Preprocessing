# WEEK 1 : Data-Acquisition-Cleaning-and-Preprocessing
# Project Overview

This project focuses on acquiring, cleaning, and preprocessing the Titanic passenger dataset using Python. The goal is to identify data quality issues, handle missing values, investigate potential outliers, and prepare the dataset for further analysis.

# Dataset

Dataset: Titanic Passenger Dataset

Source: Seaborn Data Repository

Original size: 891 rows and 15 columns

Tools: Python, Pandas, NumPy, Matplotlib, Jupyter Notebook

# Objectives

Acquire and explore the dataset.

Identify missing values and exact matching rows.

Handle missing numerical and categorical values.

Identify potential outliers using the Interquartile Range (IQR) method.

Validate the cleaned dataset.

Visualize age and fare distributions.

# Data Cleaning and Preprocessing

Loaded the Titanic dataset and examined its structure.

Filled missing age values using median imputation.

Filled missing embarkation values using mode imputation.

Replaced missing deck information with Unknown.

Retained original rows and kept exact matching rows for review instead of automatically removing them.

Identified potential outliers in age and fare using the IQR method.

Validated missing values and exported the results.

# Results

Original dataset: 891 rows and 15 columns.

Final dataset: 891 rows and 15 columns.

Missing values after cleaning: 0.

Exact matching rows remaining for review: 110.

Potential age outliers: 66.

Potential fare outliers: 116.

The potential outliers were retained because unusual values may represent genuine passenger information rather than errors.

# Visualizations

The project includes:

Age distribution histogram.

Fare boxplot showing potential outliers.

# Project Files

Week 1 Task Data Acquisition, Cleaning, and Preprocessing.ipynb — Jupyter Notebook containing the code and analysis.

raw_titanic.csv — Original dataset.

cleaned_dataset.csv — Preprocessed dataset.

cleaning_summary.json — Summary of cleaning and validation results.

missing_values_before.csv — Missing-value counts before cleaning.

missing_values_final.csv — Missing-value counts after cleaning.

age_distribution.png — Age distribution graph.

fare_boxplot.png — Fare boxplot.

Week1_Data_Cleaning_Report.docx — Project report.

# How to Run

Download or clone this repository.

Install the required libraries:

pip install pandas numpy matplotlib jupyter

Open the Jupyter Notebook.

Run the cells in order.

Review the generated dataset, summary, and graphs.

# Learning Outcomes

This project provided practical experience in data acquisition, data cleaning, missing-value imputation, duplicate inspection, outlier detection, visualization, and data validation. It also demonstrated why preprocessing decisions should be documented and checked before using data for further analysis.

# Internship

Organization: Yuva Intern
Task: Week 1 — Data Acquisition, Cleaning, and Preprocessing
