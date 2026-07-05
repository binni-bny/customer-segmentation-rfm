# Customer Segmentation using RFM Analysis & K-Means Clustering

## Problem Statement
Segment 4,338 UK e-commerce customers into distinct groups based on 
purchasing behavior to enable targeted marketing strategies.

## Dataset
Online Retail Dataset (Kaggle/UCI) - 541,909 transactions from a UK 
e-commerce store (Dec 2010 - Dec 2011).

## Tools Used
Python, pandas, numpy, matplotlib, seaborn, scikit-learn, Jupyter Notebook

## Approach
- Cleaned 541,909 transactions (removed cancellations, nulls, negatives)
- Calculated RFM (Recency, Frequency, Monetary) metrics for 4,338 customers
- Scored customers 1-4 on each RFM dimension
- Applied K-Means clustering with Elbow Method to find optimal K=4
- Labeled and visualized 4 distinct customer segments

## Customer Segments Found
- VIP Customers: 13 customers averaging £127,338 spend each
- High Value: 204 customers - recent, frequent, high spend
- Regular Customers: 3,054 customers (70%) - core customer base
- Lost/Inactive: 1,067 customers - last purchased 248 days ago

## Key Business Recommendations
- VIP: Assign dedicated account managers and exclusive rewards
- High Value: Target with premium launches to push toward VIP
- Regular: Increase frequency with loyalty programs
- Lost: Win-back campaigns with special discounts

## Skills Demonstrated
- Data cleaning on large dataset (541,909 rows)
- RFM Analysis (industry standard marketing technique)
- K-Means Clustering with Elbow Method
- Customer segmentation and business recommendations