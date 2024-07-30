# Atliqo Credit Card Market Analysis-Phase-1

## Project Overview

This project focuses on identifying the target market for Atliqo Bank's new credit card launch. The aim is to explore an untapped market segment by analyzing customer data, including age, income, credit history, and shopping behaviors. Through detailed exploratory data analysis (EDA), we provide insights into the characteristics and preferences of potential customers.

## Table of Contents
- [Data Description](#data-description)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
  - [Data Cleaning](#data-cleaning)
  - [Outlier Detection](#outlier-detection)
  - [Data Visualization](#data-visualization)
- [Key Findings](#key-findings)
- [Results](#results)
- [Repository Contents](#repository-contents)
- [How to Use](#how-to-use)
- [License](#license)
- [Contact](#contact)

## Data Description

The dataset includes the following features:
- **Age**
- **Annual Income**
- **Credit History**
- **Credit Scores**
- **Credit Limits**
- **Shopping Behaviors** (Top Categories: Electronics, Fashion & Apparel, Beauty & Personal Care)

## Exploratory Data Analysis (EDA)

### Data Cleaning
- Removed outliers using the Interquartile Range (IQR) method.
- Handled missing values to ensure data integrity.

### Outlier Detection
- Identified outliers based on business rules (e.g., outstanding debt greater than credit limit).

### Data Visualization
- Pie charts for age distribution.
- Box plots for annual income and credit limits.
- Correlation matrix to identify relationships between variables.

## Key Findings

1. **Target Market Segment**:
   - **Age Group**: 18-25 years old, accounting for ~26% of the customer base.
   - **Annual Income**: Less than $50,000.
   - **Credit History**: Limited credit history, reflected in lower credit scores and credit limits.
   - **Credit Card Usage**: Relatively low usage of credit cards compared to other age groups.
   - **Top Shopping Categories**: Electronics, Fashion & Apparel, Beauty & Personal Care.

2. **Correlations**:
   - **Credit Limit and Credit Score**: High correlation (~0.85).
   - **Credit Limit and Annual Income**: High correlation.

3. **Outlier Detection**:
   - Outliers identified using business knowledge (e.g., outstanding debt greater than credit limit).

## Results

The analysis indicates that the age group of 18-25 years is an untapped market for credit cards. This segment has limited credit history and lower credit scores, suggesting an opportunity for Atliqo Bank to offer tailored credit products to help build credit history and increase credit card usage.

## Repository Contents

- **data/**: Contains the cleaned dataset used for analysis.
- **notebooks/**: Jupyter notebooks with data cleaning, analysis, and visualization code.
- **visualizations/**: Graphs and charts generated during the analysis.
- **README.md**: This file, providing an overview of the project.

