Python-Data-Cleaning
A collection of Python-based data cleaning projects. Each project demonstrates essential techniques for preparing raw data for analysis and modeling.

Introduction
This repository contains Python-based data cleaning project that demonstrates key steps and best practices for preparing raw data for analysis or modeling. The projects here cover various aspects of data cleaning, such as handling missing values, duplicates, outliers, and ensuring data consistency.

Project : Cafe Sales
Overview
This project focuses on cleaning a dataset related to cafe sales. The dataset contains information about transactions, including the quantity of items sold, the price per unit, and the total spent.

Steps Taken
Inspecting the Data: The dataset is loaded and inspected for structure, datatypes, and basic statistics.
Handling Missing Values: Missing values in certain columns (Payment Method, Location, Item) are filled with appropriate values to prevent data loss.
Data Type Corrections: Columns with incorrect data types are converted to appropriate types for analysis.
Handling Duplicates: Duplicate records are removed from the dataset to ensure data integrity.
Feature Engineering: Missing values in Price Per Unit and Total Spent are imputed based on logical relationships between columns (e.g., calculating Total Spent as the product of Quantity and Price Per Unit).

Files Included
Cafe Sales Project (Cafe Sales.ipynb)
This file contains the code for cleaning the cafe sales data.
Dataset: Cafe Sales.csv:

How to Use
Clone the repository to your local machine.
Make sure you have Python 3.x installed along with the necessary libraries: numpy, pandas.
Run the .ipynb files in Jupyter Notebook or any other compatible Python environment.
Load the datasets (Cafe Sales.csv and Customer Care.csv) and follow the steps to clean the data.
License
This project is licensed under the MIT License - see the LICENSE file for details.
