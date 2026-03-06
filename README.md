# EDA: Energy Industry Case study

## Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of a large sales dataset (2M+ records) to uncover patterns in **sales value**.

The **EDA highlights trends, distributions, and patterns** in sales performance across different customer segments and seasons. Insights from this stage form the core of the analysis.

## Core EDA Highlights

- **Data Cleaning & Preparation:** Handling missing values, filtering relevant columns, creating a seasonality variable.
- **Descriptive Statistics:** Understanding the distribution of sales values and identifying outliers.
- **Visual Exploration:**  
  - Boxplots of sales by **customer type** and **seasonality**  
  - Histograms and density plots for sales distribution  
  - Seasonal trends and comparisons between bonus groups

## Additional Analysis (+)

A simple **Linear Regression model** was tested to explore whether customer type and seasonality could predict sales value.  
- Performance was low (R² ≈ 0.01), showing that **other business factors likely drive sales variation**.  
- Regression checks such as residual plots, Q-Q plots, and Durbin-Watson statistics were performed for completeness.

## Tools & Skills

Python • Pandas • Seaborn • Matplotlib • Scikit-learn • Statsmodels  
- Handling **very large datasets (2M+ rows)**  
- Exploratory Data Analysis (EDA)  
- Feature engineering for categorical and seasonal variables  
- Basic regression modelling and diagnostic checks  

## Dataset

- Size: 2,134,892 records   
- Time Frame: 2018–2023  

## Key Insight

**Customer type and simple seasonality alone explain very little of sales variation**, suggesting other factors such as pricing, promotions, or regional effects are more important.  

EDA remains the main focus of this project, demonstrating skills in **large-scale data exploration and visualization**.
