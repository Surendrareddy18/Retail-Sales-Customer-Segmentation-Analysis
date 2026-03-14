# Retail Sales & Customer Segmentation Analysis

## Project Overview
This project analyzes online retail transaction data to understand customer purchasing behavior, product performance, and revenue trends. The goal is to generate business insights from retail sales data using Python-based data analysis techniques.

## Tools & Technologies
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  

## Data Cleaning
The following preprocessing steps were performed:

• Removed records with missing CustomerID values  
• Removed negative quantities and invalid prices  
• Converted InvoiceDate to datetime format  
• Created new features such as Month and Year  
• Calculated TotalPrice (Quantity × UnitPrice)

## Analysis Performed

### Product Analysis
Identified top-selling products and highest revenue generating products.

### Country Analysis
Analyzed revenue contribution from different countries.

### Time Analysis
Evaluated monthly revenue trends to identify sales patterns.

### Customer Analysis
Identified top customers based on purchase value.

### Customer Segmentation
Performed **RFM Analysis (Recency, Frequency, Monetary)** to segment customers into behavioral groups.

## Key Insights

• A small number of products generate a significant portion of revenue  
• The United Kingdom contributes the majority of total sales  
• A small percentage of customers generate high revenue  
• Customer purchasing behavior varies significantly across segments  

## Project Structure
Retail-Sales-Customer-Segmentation-Analysis

Notebook/
    retail_analysis.ipynb

README.md
## Dataset

The dataset used in this project is larger than GitHub's recommended file size.
