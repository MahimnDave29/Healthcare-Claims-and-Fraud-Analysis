# Healthcare Claims and Fraud Data Analysis - EDA and PowerBI Report

## Project Overview:
This project performs Exploratory Data Analysis (EDA) on a healthcare claims dataset to uncover patterns, anomalies, and potential indicators of fraud and insights are represented in PowerBI report.

## Data Source:
https://www.kaggle.com/datasets/bonifacechosen/nhis-healthcare-claims-and-fraud-dataset/versions/1

## Report:
<img width="1430" height="812" alt="image" src="https://github.com/user-attachments/assets/724a1d4f-d7be-41fa-b021-cf1513c75445" />
<img width="1436" height="820" alt="image" src="https://github.com/user-attachments/assets/3cdc696c-0616-4e41-a068-a7ab1dadcc18" />
<img width="1437" height="797" alt="image" src="https://github.com/user-attachments/assets/0ce13034-3a3b-4ec2-bb9c-de8a18dee7d9" />
<img width="1424" height="694" alt="image" src="https://github.com/user-attachments/assets/d95f7185-27df-4e1b-9095-8ce544c90589" />

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

## Insights

**Age**  
Uniform distribution across all age groups.  
No age bias in claims.  

**Amount Billed**  
Right-skewed distribution.  
Presence of high-cost outliers.  

**Length of Stay**  
Most patients have short stays.  
Few cases with unusually long durations.  

**Cost per Day**  
Highly skewed distribution.  
Extreme values suggest potential billing inflation.

## Tech Stack:
Python(NumPy, Pandas, MatPlotlib, Seaborn), PowerBI (DAX)

