ReCell – Dynamic Pricing Model for Used Devices
Project Overview

ReCell is a machine learning project focused on predicting the prices of used and refurbished mobile devices (phones and tablets).
The goal was to help businesses and marketplaces develop data-driven pricing strategies by leveraging device specifications and usage history to determine fair, competitive prices in real time.

Problem Statement

With the rapid expansion of the used smartphone market, determining fair resale values has become challenging.
Manual pricing is often inconsistent and inefficient.
This project aims to create a predictive pricing model that can:

Accurately estimate market value for used/refurbished devices.

Support businesses in optimizing their pricing strategy.

Enhance profitability while maintaining competitiveness.

Objectives

Collect and preprocess a dataset of used device listings.

Explore trends between device attributes and resale price.

Build a linear regression model to predict device prices.

Evaluate model performance and extract actionable business insights.

Dataset Description

Size: ~3,000 records

Features:

Brand

Operating System

RAM / Storage

Battery Capacity

Screen Size

Usage History (new, lightly used, refurbished)

Selling Price (target variable)

Tools & Libraries

Programming Language: Python

Data Analysis: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Modeling: Scikit-learn (Linear Regression)

Performance Metrics: R² Score, Mean Absolute Error (MAE)

Methodology

Data Collection & Cleaning:

Removed duplicates, handled missing values, and normalized numerical fields.

Exploratory Data Analysis (EDA):

Identified relationships between specs (RAM, brand, OS) and price.

Visualized trends and distributions with Seaborn and Matplotlib.

Feature Engineering:

Encoded categorical variables.

Standardized numerical features.

Model Development:

Built a linear regression model using Scikit-learn.

Evaluated with R² and MAE to assess accuracy.

Insights Generation:

Extracted patterns that drive device value (e.g., RAM, brand premium, battery health).

Key Insights

Brand and RAM had the strongest positive correlation with resale price.

Battery health and usage history were key determinants of value depreciation.

Linear Regression achieved high interpretability and reasonable accuracy, making it ideal for price forecasting.

Business Impact

Enabled businesses to automate pricing decisions for used devices.

Improved market competitiveness through consistent and data-backed pricing.

Helped sellers identify high-value device configurations to prioritize in procurement.

Model Performance
Metric	Score
R² Score	0.84
MAE	0.09

(Replace with actual metrics from your notebook)
