# 🌍 Optimizing Renewable Energy Distribution Using Machine Learning

## 🔍 Overview

This project explores global renewable energy consumption patterns using World Bank data. The goal is to apply machine learning techniques to analyze, cluster, and eventually optimize renewable energy distribution across countries and regions.

## 🎯 Objectives

- Explore and clean renewable energy datasets
- Apply dimensionality reduction (PCA, t-SNE, ICA)
- Perform clustering (K-Means, DBSCAN)
- Forecast trends using regression models
- Derive actionable insights for policy and engineering

## 🧠 Tools & Libraries
- Python, Pandas, Numpy
- Scikit-learn, Matplotlib, Seaborn
- PCA, K-Means, DBSCAN, Regression
- Google Colab (for execution)

## 📅 Day 1 – 04/05/2025
### ✅ What I Did
- Created project structure and GitHub README
- Loaded World Bank renewable energy CSV in Colab
- Explored columns and visualized top 10 countries for 2020

### 🧠 What I Learned
- World Bank datasets use metadata rows (need to skip)
- Many countries have missing values—need strategy to handle them

### 📍 Next Steps
- Clean missing data and choose consistent year range
- Visualize country clusters or regional differences

## 📅 Day 2 – 04/07/205
### ✅ What I Did
- Visualized missing data trends
- Selected relevant years (2000–2020)
- Dropped countries with excessive nulls
- Filled missing values with row-wise mean

### 🧠 What I Learned
- Data quality varies significantly by country
- Row-wise mean works well for small gaps, but regional imputation could be more precise

