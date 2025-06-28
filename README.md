# Superstore Sales Analysis

This project is an exploratory data analysis (EDA) of the Superstore sales dataset to understand patterns in sales, profits, shipping modes, and other key metrics. The dataset was imported from Kaggle, loaded into a MySQL database for querying, cleaned, and then analyzed using Python pandas in a Jupyter Notebook.

---

## Dataset

- **Source**: [Superstore Dataset (Kaggle)](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- The dataset contains retail transactional records, including:
  - Order IDs
  - Order dates
  - Ship dates
  - Shipping modes
  - Customer details
  - Product categories and subcategories
  - Sales, discounts, profit
  - Regional details

---

### Project Steps

### 1️⃣ Download Data

- Downloaded the CSV from Kaggle.
- File name: `Superstore.csv`

### 2️⃣ Set Up MySQL

- Installed MySQL on macOS via Homebrew.
- Created the `Superstore` database:
  ```sql
  CREATE DATABASE Superstore;
  USE Superstore;
-Created a table superstore_sales matching the CSV columns.
Loaded the CSV into the table using either MySQL Workbench import or LOAD DATA INFILE.

### 3️⃣ Verify MySQL Connection
### 4️⃣ Python Environment
Used macOS system Python:
Python 3.9
JupyterLab

### Files in this Repository
Superstore-Analysis.ipynb — Jupyter Notebook with full EDA code
Superstore.csv — original raw dataset
superstore_cleaned.csv — cleaned dataset after removing duplicates and correcting data types
requirements.txt — list of required Python modules

### Notes
This analysis is exploratory only; no predictive modeling was performed yet.

## Credits
Dataset: Kaggle user vivek468

# Coded by priyanshupritam.
