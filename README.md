# new-data-cleaning-project
Dataset for Data Analytics - Cleaning
A simple data cleaning project using Python and pandas.

Files:
datacleaning.py — cleaning script
DatasetforDataAnalytics_cleaned.csv — cleaned dataset

What it does:
Drops rows with too many missing values
Fills missing values (median for numeric, mode for categorical)
Removes duplicates
Standardizes text (lowercase, trimmed)
Removes outliers using IQR
Saves the cleaned dataset

How to Run:
bashpip install pandas numpy
python datacleaning.py

Author:
[Muhammad Faizan Azeemi]
