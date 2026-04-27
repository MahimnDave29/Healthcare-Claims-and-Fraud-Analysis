# Exploratory Data Analysis on Healthcare Claims Data

## Project Overview:
This project performs Exploratory Data Analysis (EDA) on a healthcare claims dataset to uncover patterns, anomalies, and potential indicators of fraud.

## Data Source:
https://www.kaggle.com/datasets/bonifacechosen/nhis-healthcare-claims-and-fraud-dataset/versions/1

## Data Preprocessing

Converted date columns to datetime format.
Verified data types.
Checked for missing values. No missing data found.
Checked for duplicate values. No duplicates found.
Dataset is clean.

Created new features:
Length of Stay,
Cost per Day

## Analysis Performed
### Univariate Analysis
Distribution of Age, Amount Billed, Length of Stay, and Cost per Day
Descriptive statistics

### Bivariate Analysis
Relationship between:
Fraud Type vs Billing Amount, Diagnosis vs Fraud Patterns, and Length of Stay vs Cost

### Visualization
Histograms,
Boxplots,
Bar charts,
Stacked distributions,
Heatmaps

## Insights: 
Age:
Uniform distribution across all age groups
No age bias in claims
Amount Billed:
Right-skewed distribution
Presence of high-cost outliers
Length of Stay:
Most patients have short stays
Few cases with unusually long durations
Cost per Day:
Highly skewed distribution
Extreme values suggest potential billing inflation

## Tech Stack:
Python(NumPy, Pandas, MatPlotlib, Seaborn)

