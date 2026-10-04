# Customer Churn — Data Quality and Exploratory Analysis

## Objective
Audit and clean a synthetic customer churn dataset, document data-quality decisions, and identify initial patterns.

## Dataset
`customer_churn_sample.csv` is the supplied synthetic customer churn dataset.

## Work completed
- Profiled columns and data types
- Checked missing values
- Checked duplicate rows and duplicate CustomerID values
- Checked numeric outliers using the IQR rule
- Standardized leading/trailing whitespace in text fields
- Did not invent, impute, or randomly replace customer values
- Calculated summary statistics
- Reviewed the churn distribution

## Key validation result
The supplied dataset contains 15 records and 11 columns. There are no missing values, no duplicate rows, and no duplicate CustomerID values. The IQR check found no numeric outliers.

## Initial pattern
There are 7 customers marked `Yes` for churn and 8 marked `No`.

## Files
- `customer_churn_cleaned.csv` — cleaned dataset
- `customer_churn_analysis.ipynb` — analysis notebook
- `data_dictionary.xlsx` — column definitions
- `exception_log.xlsx` — validation and cleaning log
