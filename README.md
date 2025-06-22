# 🧠 Customer Segmentation using KMeans Clustering

## 📌 Overview

This project focuses on customer segmentation using clustering techniques, particularly **KMeans**, to identify distinct groups of customers based on their purchasing behavior. This type of segmentation helps businesses better understand their customer base and tailor their marketing strategies accordingly.

The dataset is sourced from Kaggle and contains anonymized financial data for a set of customers.

## 📊 Dataset

- **Source**: [Kaggle - Credit Card Dataset](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)
- **Features Include**:
  - Balance
  - Purchases
  - Cash Advance
  - Credit Limit
  - Tenure
  - And more...

## 🧰 Tools & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

## 🗂️ Project Structure

### 1. Preparing the Project
- Connection to Kaggle API
- Downloading dataset
- Importing necessary libraries

### 2. Data Analysis
- Understanding the structure and variables
- Checking for missing/unique values
- Statistical summaries and dtype checks

### 3. Data Preprocessing
- Imputation of missing values
- Encoding categorical variables (if any)

### 4. Exploratory Data Analysis (EDA)
- Visualizations: Distribution plots, boxplots
- Correlation analysis to detect multicollinearity

### 5. Modeling Preparation
- Feature Scaling (StandardScaler)
- Determining the optimal number of clusters (Elbow Method)

### 6. KMeans Clustering
- Applying KMeans to segment customers
- Appending cluster labels to original data
- Visualizing the resulting clusters

## 📈 Key Results

- Customers are grouped into distinct clusters with similar behaviors.
- Optimal number of clusters determined using the elbow method.
- Insights can be used to personalize marketing and improve customer retention.


