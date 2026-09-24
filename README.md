# Python Data Cleaning Project: Cafe Sales

A Python data cleaning project that shows how to prepare a raw, messy dataset for analysis. The project cleans a cafe sales dataset using pandas and numpy.

---

## Overview

The dataset contains cafe transaction records, including the item sold, quantity, price per unit, total spent, payment method and location. The raw data has missing values, incorrect data types and duplicate records, and this project cleans all of them.

---

## Steps Taken

1. **Inspecting the data:** Load the dataset and check its structure, data types and basic statistics.
2. **Handling missing values:** Fill missing values in `Payment Method`, `Location` and `Item` so that no records are lost. The exact values used are shown in the notebook.
3. **Correcting data types:** Convert columns with the wrong data type into the correct ones for analysis.
4. **Handling duplicates:** Remove duplicate records to keep the data reliable.
5. **Deriving missing numeric values:** Fill missing values in `Price Per Unit` and `Total Spent` using the relationship between columns (`Total Spent = Quantity × Price Per Unit`).

---

## Project Structure

```
Data_Cleaning_Project/
│
├── data/
│   ├── raw/
│   │   └── Cafe Sales.csv        # original, uncleaned dataset
│   └── clean/                    # cleaned dataset after processing
│
├── .gitignore
├── Cafe Sales.ipynb              # data cleaning notebook
├── LICENSE
└── README.md
```

---

## Dataset

- **Raw file:** `data/raw/Cafe Sales.csv`
- **Cleaned output:** saved in `data/clean/`

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/atharvbajpai-web/Data_Cleaning_Project.git
   cd Data_Cleaning_Project
   ```
2. Make sure Python 3.x is installed, then install the required libraries:
   ```bash
   pip install numpy pandas jupyter
   ```
3. Open `Cafe Sales.ipynb` in Jupyter Notebook (or any compatible environment).
4. Run all cells. The notebook reads `data/raw/Cafe Sales.csv` and cleans it step by step.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
