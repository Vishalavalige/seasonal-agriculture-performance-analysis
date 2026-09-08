# Seasonal Agriculture Performance Analysis

**VOIS AICTE Batch 1 2026–2027 — Major Project**
**Author:** Valige Vishala, Sana Engineering College, Kodad

## Project Overview

This project analyzes a dataset of 4,000 farm records spanning 8 states, 10 districts, 8 crops and 3 growing seasons (Kharif, Rabi, Zaid) to investigate how agricultural performance varies across seasons and identify meaningful patterns, trends, relationships and differences in the data.

## Problem Statement

Agricultural activities are influenced by seasonal variations in environmental conditions, farming practices, resource availability and market conditions. Raw agricultural data does not clearly explain how performance changes across seasons. This project analyzes the dataset to investigate those seasonal differences using data-driven methods.

## Repository Contents

| File | Description |
|---|---|
| `Seasonal_Agriculture_Performance_Analysis.ipynb` | Full analysis notebook (data cleaning, EDA, statistical testing, visualizations, insights) |
| `seasonal_agriculture_performance_dataset.csv` | Source dataset (4,000 rows, 28 columns) |
| `Seasonal_Agriculture_Performance_Analysis_PPT.pptx` | Project submission presentation |

## Methodology

1. Data cleaning — missing value treatment, duplicate checks, outlier capping (IQR method)
2. Exploratory Data Analysis — univariate, bivariate, and multivariate analysis
3. Statistical testing — one-way ANOVA to test for significant seasonal differences in yield and profit
4. Visualization — boxplots, heatmaps, pair plots, correlation matrices
5. Insights and recommendations based on evidence from the data

## Key Findings

- Yield and profit differ significantly across seasons (ANOVA, p < 0.0001)
- Kharif is the strongest season for both yield and profit; Zaid is the weakest
- The share of loss-making farms rises steadily: 42% (Kharif) → 51% (Rabi) → 64.5% (Zaid)
- Some crops are far more season-sensitive than others
- Regional (state-level) patterns are not fully uniform

## Tools Used

Python 3 · Pandas · NumPy · Matplotlib · Seaborn · SciPy · Jupyter Notebook / Google Colab

## How to Run

1. Open `Seasonal_Agriculture_Performance_Analysis.ipynb` in Google Colab or Jupyter
2. Upload `seasonal_agriculture_performance_dataset.csv` into the same session/folder
3. Run all cells top to bottom
