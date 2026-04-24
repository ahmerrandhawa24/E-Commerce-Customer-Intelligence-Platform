# E-Commerce Customer Intelligence Platform

## Project Overview

This project is an **end-to-end AI + Data Engineering system** designed to analyze customer behavior in an e-commerce environment.

The system collects raw data, processes it using an ETL pipeline, stores it in a database, and applies Machine Learning to generate business insights.

---

## Project Goals

* Understand customer behavior
* Segment customers into meaningful groups
* Predict customer churn
* Recommend products based on purchase patterns
* Visualize insights using a dashboard

---

## Project Architecture

```
Raw Data (Kaggle - Instacart)
        ↓
Data Cleaning & Transformation (Python - Pandas)
        ↓
Feature Engineering (RFM, CLV, Trends)
        ↓
Data Storage (PostgreSQL)
        ↓
Machine Learning Models
        ↓
Power BI Dashboard (Final Output)
```

---

## Dataset

Dataset used: **Instacart Online Grocery Basket Analysis**

Files used:

* aisles.csv
* departments.csv
* orders.csv
* order_products__prior.csv
* products.csv

---

## ETL Pipeline

### Extract

* Loaded CSV data from Kaggle

### Transform

* Handled missing values
* Removed duplicates
* Converted data types
* Created new features

### Feature Engineering

* Recency (last purchase)
* Frequency (number of orders)
* Monetary (total spend)
* Customer Lifetime Value (CLV)
* Average order value

### Load

* Stored processed data into PostgreSQL

---

## Machine Learning Models

### 1. Customer Segmentation

* Algorithm: K-Means Clustering
* Output:

  * High-value customers
  * Loyal customers
  * At-risk customers
  * Low engagement users

---

### 2. Recommendation System

* Method: Association Rule Mining (Apriori)
* Output:

  * “Customers who bought X also bought Y”

---

### 3. Churn Prediction

* Algorithm: Random Forest Classifier
* Output:

  * Churn probability
  * High-risk customers

---

## Dashboard (Power BI)

The dashboard provides:

* Customer Segments
* Revenue Insights
* Churn Distribution
* High-Risk Customers
* Product Recommendations

---

