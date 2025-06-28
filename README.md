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

## Project Steps

### 1️⃣ Download Data

- Downloaded the CSV from Kaggle.
- File name: `Superstore.csv`

### 2️⃣ Set Up MySQL

- Installed MySQL on macOS via Homebrew.
- Created the `Superstore` database:
  ```sql
  CREATE DATABASE Superstore;
