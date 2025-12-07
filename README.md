# Day-1-of-Practice

Wine Dataset Analysis – Day 1 of Practice

This project is part of my daily data analysis & machine learning practice series.
The goal was to explore the Wine dataset, analyze feature behavior, visualize patterns, and understand the impact of feature scaling on model preparation.

📌 Project Overview

This analysis focuses on three key columns from the Wine dataset:

Class label

Alcohol

Malic Acid

The core objective was to:

Understand feature distributions

Visualize relationships between features

Apply proper preprocessing steps

Compare raw vs. scaled feature behavior

Prepare the data correctly for ML models

📊 Steps Performed
1. Data Loading

Loaded the dataset using Pandas

Selected specific columns

Assigned meaningful column names

2. Exploratory Data Analysis (EDA)

KDE plots for Alcohol and Malic Acid

Scatter plot to visualize class separation

Observed density, spread, and class grouping patterns

3. Train–Test Split

Separated features and target

Applied a 70:30 split

Ensured the train-test workflow followed ML best practices

4. Feature Scaling

Used MinMaxScaler

Fitted scaler only on training data

Transformed both training and test sets

Created scaled DataFrames for clarity

Compared statistical summaries before vs. after scaling

5. Visual Comparison (Before vs After Scaling)

Scatter plots to show how scaling normalizes feature ranges

KDE plots for Alcohol & Malic Acid before and after scaling

Highlighted the importance of scaled numeric inputs for ML algorithms

📌 Why This Matters

This exercise reinforces essential ML preprocessing steps:

Always split first, then scale

Fit scaler on training data only

Check distributions to avoid misleading model behavior

Understand how scaling affects distance-based algorithms

These skills form the foundation for building accurate ML models.

🛠 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📁 Files in This Repository

days_25_of_practice.py — Full Python script

Plots generated during the analysis

README (this file)
