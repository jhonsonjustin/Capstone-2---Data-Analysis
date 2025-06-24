# Capstone-2---Data-Analysis
A data analytics project to help PT TransJakarta understand trip completion behavior among passengers. This includes identifying incomplete trips, analyzing age and payment behavior, and visualizing usage patterns to support operational decisions.

# 🚍 TransJakarta Trip Analysis (Jupyter Notebook)

This repository contains a data analysis notebook that explores passenger transaction data from PT TransJakarta. The main goal is to identify patterns in incomplete trips (tap-in without tap-out), analyze user demographics, and generate insights to improve service efficiency and reduce potential revenue loss.

## 📘 Notebook File

- `Capstone2_Justin.ipynb`  
  Contains data cleaning, feature engineering, exploratory data analysis (EDA), and classification of trip status.

## 🔍 Key Analyses

- Classification of trips into:
  - Complete Paid
  - Complete Free
  - Incomplete
  - Incomplete Paid (edge cases)
- Analysis of age distribution by trip status
- Free vs Paid trip segmentation
- Trip behavior across hours and corridors
- Payment pattern by card-issuing bank

## 💡 Key Findings

- Approximately **3.5%** of trips were incomplete, often involving users aged **30–45**
- Some corridors show high volume of incomplete trips
- **Bank DKI, Online, and BNI** users dominate the free trip segment
- Incomplete trips peak during rush hours (5–7 AM and 4–5 PM)
