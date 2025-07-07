# ETL and Data Cleanup Project

This repository contains a data cleaning and ETL (Extract, Transform, Load) project using Python and pandas. The project demonstrates how to handle messy real-world data by performing data cleanup, transformation, and loading the cleaned data into a SQLite database.

## Project Overview

- **Dataset:** A synthetic customer sales dataset with 1000 rows, containing common data quality issues such as missing values, inconsistent formatting, duplicates, invalid entries, and mixed date formats.  
- **Goal:** Clean and preprocess the dataset, ensuring consistency and usability for downstream analysis.  
- **Technologies:** Python, pandas, SQLite  

## Key Steps in the Project

1. **Loading Data:** Import the messy CSV dataset using pandas.  
2. **Handling Missing Values:** Fill or assign new customer IDs for missing values.  
3. **Data Standardization:** Normalize text fields like product categories, country names, and customer names.  
4. **Email Cleaning:** Standardize emails and identify duplicates.  
5. **Removing Invalid Data:** Filter out negative purchase amounts.  
6. **Date Parsing:** Parse multiple date formats and normalize datetime columns.  
7. **Exporting Data:** Save cleaned data to a SQLite database and as a CSV backup.  

## Usage

To run the project, clone this repository and run the Jupyter notebook `ETL and Data Cleanup.ipynb`. The notebook is fully annotated with explanations for each step.  

Commands to run in your terminal:  

- git clone https://github.com/rudolphhaink/ETL-and-Data-Cleanup.git  
- cd ETL-and-Data-Cleanup  
- jupyter notebook ETL and Data Cleanup.ipynb  

## Dependencies

- pandas  
- sqlite3 (standard Python library)  
- Jupyter Notebook or Jupyter Lab  

Install pandas with pip if needed:  

- pip install pandas  

## 👤 Author

Rudolph Haink  
[LinkedIn](https://www.linkedin.com/in/rudolph-haink-a5454564/)

