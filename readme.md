# Telco Advertising Revenue Prediction using Machine Learning

## Overview
This project applies machine learning to analyze real-world telecommunications advertising data in Indonesia to identify key revenue drivers and support data-driven decision-making. The goal is not only to predict revenue but to understand **why revenue changes**, enabling more effective advertising and business strategies.

This work is based on my IEEE-published research on applying machine learning for advertising optimization in the telco industry.

---

## Problem Statement
Telecommunication companies invest heavily in advertising across multiple channels, but understanding which factors truly drive revenue is challenging due to noisy, incomplete, and complex real-world data.

This project aims to:
- Identify the key drivers of advertising revenue  
- Predict revenue performance using machine learning  
- Provide actionable insights for marketing and business strategy  
- Compare model performance for accuracy vs practicality  

---

## Dataset
The dataset consists of real-world telecom business data including:

- Advertising network performance  
- Billing and campaign success metrics  
- Revenue-related indicators  
- Multiple messy datasets merged and cleaned  
- ~50,000+ records  

Due to confidentiality, raw data is not publicly shared.

---

## Methodology

### 1. Data Processing
- Data cleaning and preprocessing  
- Handling missing and noisy values  
- Dataset merging and transformation  
- Feature engineering  

### 2. Modeling
Several machine learning models were tested and compared:

- Linear Regression  
- Random Forest  
- Gradient Boosting  
- CatBoost (Best Performing)  

### 3. Evaluation Metrics
- R² Score  
- Mean Absolute Error (MAE)  
- Model efficiency and training time  
- Practical interpretability for business use  

---

## Results

- **Best Model:** CatBoost Regressor  
- **R² Score:** ~0.82  
- Successfully identified key revenue-driving factors:
  - Advertising network performance  
  - Successful billing metrics  
- Demonstrated strong predictive performance on real-world noisy data  
- Provided actionable business insights rather than only predictions  

---

## Key Insights

- Revenue is heavily influenced by **Ad Network performance and billing success rate**  
- Data quality significantly impacts predictive accuracy  
- Machine learning can support **marketing optimization and revenue strategy**  
- Interpretable models are important for business decision-making  

---

## Tech Stack

- Python  
- Pandas / NumPy  
- Scikit-learn  
- CatBoost  
- Matplotlib / Seaborn  
- Jupyter Notebook  


---

## Research Publication

This project is based on my IEEE-indexed research:

**"Using Machine Learning for Shaping the Future of Advertising for Telco Industry in Indonesia"**

The study demonstrates how machine learning can identify revenue drivers and support strategic advertising decisions.

---
