# SWYNEX - Data Cleaning & Preparation

## Task 1: Data Cleaning & Preparation

This project was completed as part of my Data Analytics Internship at SWYNEX Technologies.

## Dataset

I used the public Titanic dataset for data cleaning and preparation.

- Dataset: Titanic Passenger Dataset
- Records: 891
- Tool Used: Microsoft Excel

## Data Quality Checks

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent values
- Invalid values

## Data Cleaning Performed

### 1. Missing Values

- Age: 177 missing values were replaced with the median age (28).
- Cabin: 687 missing values were replaced with `Unknown`.
- Embarked: 2 missing values were replaced with the most frequent value, `S`.

### 2. Duplicate Records

No duplicate records were found.

### 3. Data Consistency

- Sex contains `male` and `female`.
- Pclass contains `1`, `2`, and `3`.
- Survived contains `0` and `1`.
- Embarked contains `S`, `C`, and `Q`.

### 4. Data Validation

Age and Fare values were checked for valid ranges.

- Age: 0.42 to 80
- Fare: 0 to 512.3292

No invalid values requiring correction were identified.

## Files

- `SWYNEX_Titanic_Cleaned.csv` - Cleaned dataset
- `README.md` - Project documentation

## Outcome

The raw Titanic dataset was cleaned and prepared for further analysis by handling missing values, checking duplicates, validating data ranges, and ensuring consistent categorical values.

## Internship

Completed as part of the Data Analytics Internship at **SWYNEX Technologies**.
