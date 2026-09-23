# 🐍 Python Data Cleaning Project

A collection of **Python-based data cleaning project** focused on transforming raw and inconsistent datasets into clean, structured, analysis-ready data.

This project demonstrates practical data-cleaning techniques commonly used by data analysts, including **missing-value treatment, data-type correction, duplicate removal, data validation, and feature engineering**.

---

## 📌 Project: Cafe Sales Data Cleaning

### 📖 Overview

This project focuses on cleaning and preparing a **Cafe Sales dataset** containing transaction-level information such as items purchased, quantity, price per unit, payment method, location, and total amount spent.

The goal is to transform messy raw data into a **reliable and analysis-ready dataset** while preserving as much valid information as possible.

---

## 🎯 Objectives

* Understand the structure and quality of the raw dataset
* Identify missing and inconsistent values
* Correct incorrect data types
* Remove duplicate records
* Handle missing values using logical approaches
* Validate relationships between columns
* Create derived values where appropriate
* Prepare the dataset for further analysis

---

## 🛠️ Data Cleaning Process

### 1. Data Inspection

* Loaded the dataset using **Pandas**
* Checked the number of rows and columns
* Examined column names and data types
* Generated basic descriptive statistics
* Identified missing and inconsistent values

### 2. Handling Missing Values

Missing values were identified and treated based on the nature of each column.

Examples include:

* `Payment Method`
* `Location`
* `Item`
* `Price Per Unit`
* `Total Spent`

Rather than blindly deleting rows, logical methods were used wherever possible to preserve useful records.

### 3. Data Type Correction

Columns containing incorrect or inconsistent data types were converted into appropriate formats to make them suitable for analysis.

### 4. Duplicate Removal

Duplicate records were identified and removed to improve **data integrity and reliability**.

### 5. Feature Engineering

Logical relationships between columns were used to derive or validate values.

For example:

```text
Total Spent = Quantity × Price Per Unit
```

This relationship was used to handle missing values and validate existing transaction data.

### 6. Data Validation

The cleaned dataset was checked for:

* Remaining missing values
* Duplicate records
* Invalid data types
* Inconsistent values
* Logical inconsistencies between related columns

---

## 📂 Project Structure

```text
Python-Data-Cleaning/
│
├── Cafe Sales/
│   ├── Cafe Sales.ipynb
│   └── Cafe Sales.csv
│
├── README.md
└── LICENSE
```

---

## 📁 Files Included

### `Cafe Sales.ipynb`

Jupyter Notebook containing the complete Python data-cleaning process.

### `Cafe Sales.csv`

Raw dataset used for the project.

---

## 🧰 Tools & Technologies

* **Python**
* **Pandas**
* **NumPy**
* **Jupyter Notebook**

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
```

### 2. Install the required libraries

```bash
pip install pandas numpy jupyter
```

### 3. Open Jupyter Notebook

```bash
jupyter notebook
```

### 4. Open

```text
Cafe Sales.ipynb
```

and run the notebook cells sequentially.

---

## 💡 Key Skills Demonstrated

This project demonstrates practical experience with:

* Data Exploration
* Data Cleaning
* Missing Value Treatment
* Duplicate Detection & Removal
* Data Type Conversion
* Data Validation
* Feature Engineering
* Pandas
* NumPy
* Jupyter Notebook



## 👤 Author

**Atharv**

Aspiring Data Analyst | Python | SQL | Power BI

---



