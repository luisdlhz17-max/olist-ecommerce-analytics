# Olist E-commerce Analytics Portfolio

## Overview

This repository contains data analytics projects developed using the Brazilian E-Commerce Public Dataset by Olist. The projects explore data quality, business performance, and customer behavior through Python-based analysis and machine learning.

## Projects

### 1. Data Quality and Business Analytics

**Notebook:** `01_Olist_Ecommerce_Data_Quality_and_Business_Analytics.ipynb`

Key topics:
- Data quality assessment and duplicate detection.
- Primary key and referential integrity checks.
- Monthly order and merchandise value analysis.
- Product category performance.
- Pareto analysis of product categories.

**Tools:** Python, Pandas, Matplotlib.

### 2. Customer Segmentation with K-Means

**Notebook:** `02_Olist_Customer_Segmentation_KMeans.ipynb`

Key topics:
- Customer-level RFM feature engineering: recency, frequency, and monetary value.
- Exploratory data analysis.
- Log transformation and feature scaling.
- K-Means clustering and silhouette score evaluation.
- Customer segment profiling and business interpretation.

**Tools:** Python, Pandas, Matplotlib, Scikit-learn.

### 3. E-commerce Delivery Performance Analysis

**Notebook:** `03_Olist_Delivery_Performance_Analysis.ipynb`

**Objective:** Analyze historical delivery performance in the Brazilian E-Commerce dataset to identify patterns associated with late deliveries and operational improvement opportunities.

**Key topics:**
- Data quality assessment and timestamp validation.
- Delivery performance KPIs, including late-delivery rate and average delivery time.
- Monthly delivery performance trends.
- Fulfillment stage duration analysis.
- Geographic comparison of delivery performance across Brazilian states.
- Business findings, operational implications, and recommendations.

**Tools:** Python, Pandas, Matplotlib.

**Key findings:**
- 8.11% of analyzed delivered orders arrived after the estimated delivery date.
- March 2018 recorded a 21.36% late-delivery rate.
- Late orders had substantially longer average carrier-to-customer durations than on-time or early orders.
- Delivery performance varied across customer states, with different priorities emerging from late-delivery rates and absolute late-order volumes.

**Note:** Findings are descriptive and do not establish causation. Timestamp inconsistencies and extreme durations are documented as data-quality limitations.

## Dataset

The analysis uses the Brazilian E-Commerce Public Dataset by Olist, available on Kaggle:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The notebooks download the dataset through KaggleHub. Follow Kaggle's access requirements and the dataset's terms of use when reproducing the analysis.

## How to Run

1. Open a notebook in Google Colab.
2. Install any dependencies required by the notebook.
3. Run the notebook cells in order.
4. Make sure the dataset download and access steps complete successfully.

## Disclaimer

The findings are descriptive and based on historical data. Customer segments reflect patterns in the analyzed dataset and should not be interpreted as causal effects or guaranteed future behavior.

## Author

**Luis José De La Hoz Santiago**  
Data Analytics | Business Intelligence | Data Science

