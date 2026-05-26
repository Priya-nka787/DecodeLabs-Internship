# Task 2: Data Cleaning & Preprocessing
# completed by Priyanka Choudhary

## Objective
Prepare the dataset for analysis by cleaning and organizing data.

## Dataset
- Name: Titanic Dataset
- File: `data/dataset.csv`

## Files
- `data/dataset.csv` - Raw dataset
- `notebook/task2_data_cleaning.ipynb` - Main notebook

## Cleaning Steps Performed
- Filled 177 missing Age values with median (28)
- Filled 2 missing Embarked values with mode (S)
- Dropped Cabin column (77% data missing)
- No duplicate rows found
- Final shape: 891 rows × 11 columns

## Libraries Used
- pandas, numpy