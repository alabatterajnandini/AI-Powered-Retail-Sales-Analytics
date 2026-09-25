# AI-Powered Retail Sales Analytics and Anomaly Detection

## Project Overview

This project is an AI-powered retail sales analytics system developed as part of the AICTE | IBM SkillsBuild Data Analytics with AI Academic Internship 2026.

The project analyzes retail sales data to identify important business patterns, sales trends, profitability, and unusual transactions. It combines traditional data analytics techniques with machine learning to generate meaningful business insights.

## Objectives

The main objectives of this project are:

- To clean and preprocess retail sales data.
- To perform exploratory data analysis.
- To calculate important sales and profit KPIs.
- To analyze sales performance across categories and regions.
- To study monthly sales trends.
- To analyze profitability at the sub-category level.
- To detect unusual sales transactions using Artificial Intelligence.
- To predict sales using a machine learning model.
- To generate useful business insights from the analyzed data.

## Dataset

The project uses the **Sample Superstore Dataset**.

The dataset contains retail transaction information such as:

- Order ID
- Order Date
- Ship Date
- Customer information
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit

### Dataset Source

https://github.com/leonism/sample-superstore

### Direct Dataset

https://raw.githubusercontent.com/leonism/sample-superstore/master/data/superstore.csv

The dataset is loaded directly in the Jupyter Notebook from the public dataset URL.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## AI and Machine Learning Techniques

### 1. Isolation Forest

Isolation Forest is used for anomaly detection.

It analyzes the following features:

- Sales
- Quantity
- Discount
- Profit

The model identifies transactions that behave differently from the majority of the dataset.

### 2. Random Forest Regressor

Random Forest Regressor is used for sales prediction.

The model learns relationships between sales and other transaction-related features and evaluates the prediction performance using:

- Mean Absolute Error (MAE)
- R² Score

## Data Analysis Performed

The project performs the following analysis:

### Sales Analysis

- Total Sales
- Total Profit
- Total Orders
- Total Quantity
- Average Order Value

### Category Analysis

Sales and profit are analyzed for different product categories.

### Regional Analysis

Sales performance is compared across different regions.

### Monthly Trend Analysis

Monthly sales trends are visualized to understand changes in sales over time.

### Profitability Analysis

Profit is analyzed at the sub-category level to identify high-profit and low-profit areas.

## Project Workflow

```text
Dataset
   ↓
Data Loading
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
KPI Calculation
   ↓
Data Visualization
   ↓
Profitability Analysis
   ↓
AI Anomaly Detection
   ↓
Sales Prediction
   ↓
Business Insights
