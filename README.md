# SWYNEX Task 1 - Data Cleaning & Preparation

## Overview
This project was completed as part of the SWYNEX Internship Task 1: Data Cleaning & Preparation.

The Titanic public dataset was cleaned and prepared using Python and Pandas in Jupyter Notebook.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Dataset
- Dataset: Titanic Dataset
- Rows: 891
- Original Columns: 12

## Data Cleaning Performed

| Issue | Action Taken |
|---|---|
| Missing Age values | 177 missing values were filled with the median age (28) |
| Missing Cabin values | Cabin column was removed due to a high number of missing values (687) |
| Missing Embarked values | 2 missing values were filled with the mode (`S`) |
| Duplicate records | Checked; 0 duplicate rows were found |
| Data types | Checked and confirmed as appropriate |

## Final Result
- Rows: 891
- Columns: 11
- Missing values: 0
- Duplicate rows: 0

## Files Included
- `Titanic-Dataset.csv` — Original dataset
- `Titanic_Cleaned.csv` — Cleaned dataset
- `Titanic_Cleaned_Dataset.ipynb` — Python/Jupyter Notebook containing the cleaning process

## Conclusion
The dataset was successfully cleaned and prepared for further analysis. Missing values were handled, unnecessary data was removed, duplicates were checked, and data types were verified.
