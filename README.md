# 🎯What You're Aiming For.
In this checkpoint, we are going to work on the 'Credit Card Dataset for Clustering' dataset provided by Kaggle. This project aims to develop customer segmentation to define marketing strategies.

# Dataset Description.
This dataset was derived and simplified for learning purposes. It includes usage behavior of about 9000 active credit card holders during a six-month period. This case requires developing customer segmentation to guide marketing strategies.

## ➡️ Dataset Link: [Credit Card Dataset for Clustering (https://drive.google.com/file/d/1Yb4ljRXRQfTmcLOac_5w-pLpvPdFPvnc/view?usp=sharing)]

# Columns Explanation.
- **CUST_ID**: Identification of Credit Card holder (Categorical)
- **BALANCE_FREQUENCY**: How frequently the Balance is updated, score between 0 and 1 (1 = frequently updated, 0 = not frequently updated)
- **PURCHASES**: Amount of purchases made from the account 
- **CASH_ADVANCE**: Cash in advance given by the user
- **CREDIT_LIMIT**: Limit of Credit Card for the user 
- **PAYMENTS**: Amount of Payment done by the user 

# ℹ️Instructions.

### 1. Import Data and Perform Basic Data Exploration
- Load the dataset and explore its basic structure and statistics.
- Display general information and summary statistics about the dataset.

### 2. Data Preparation
- Import the dataset and perform basic exploration.
- Handle corrupted and missing values.
- Encode categorical features.
- Handle outliers and remove duplicates.
- Select the target variable and feature set.
- Split the dataset into training and test sets.

### 3. Hierarchical Clustering
- Perform hierarchical clustering to identify the inherent groupings within your data using two features (e.g., 'PURCHASES' and 'CREDIT_LIMIT').
- Plot the clusters using a dendrogram.

### 4. K-means Clustering
- Perform partitional clustering using the K-means algorithm.
- Plot the clusters.

### 5. Find the Best k Value
- Use the Elbow Method to find the optimal number of clusters (k).
- Plot the clusters again with the optimal k value.

### 6. Interpret the Results
- Analyze and interpret the results of both hierarchical and K-means clustering.

# 🛠️Tools and Libraries
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **SciPy**: Scientific computing
- **Scikit-learn**: Machine learning algorithms

# Libraries Used.
```
python
import pandas as pd
import numpy as np
from scipy import stats
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.cluster import KMeans
from scipy import stats
from sklearn.preprocessing import StandardScaler from scipy.cluster.hierarchy import dendrogram, linkage
```
