# Bangladesh Crime Data — K-Means Clustering
Exploratory data analysis and K-Means clustering on a Bangladesh crime incident dataset to profile district-level crime patterns.
## Overview
- Dataset: 6,574 rows × 26 columns
- Dropped irrelevant/redundant columns (index, incident_week, population counts, incident_district)
- Cleaned column naming, handled duplicates, inconsistent values, missing values, and outliers
- Encoding and scaling applied before clustering
## Workflow
1. EDA — insights and irregularities in the raw dataset, addressed appropriately
2. Data Cleaning — deduplication, inconsistent/invalid value handling, missing value imputation, outlier treatment, month converted to categorical, encoding, scaling
3. K-Means Clustering — tuned using at least two evaluation metrics, final clusters visualized
4. Cluster Profiling — characteristics of each cluster analyzed
5. Conclusion & Insight
## Tech Stack
Python Pandas NumPy scikit-learn Matplotlib
## Data
Bangladesh_Crime_Dataset_B.csv
