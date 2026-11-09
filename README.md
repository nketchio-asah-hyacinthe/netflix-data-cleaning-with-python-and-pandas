# Netflix Data Cleaning with Python and Pandas

A portfolio project demonstrating a documented data cleaning workflow with Python and pandas.

I inspect, clean, and validate a Netflix catalog dataset while preserving useful records and explaining the data quality decisions.

## Project highlights

- Inspected the dataset’s shape, columns, data types, and summary statistics.
- Investigated duplicate rows and missing-value placeholders.
- Preserved unavailable director and country values as `Not Given` rather than guessing or deleting records.
- Converted `date_added` from text to a datetime type.
- Removed leading and trailing spaces from text columns.
- Compared the original and cleaned data.
- Exported the cleaned dataset as a separate CSV file.

## Results

- 8,790 rows and 10 columns retained.
- 0 exact duplicate rows identified.
- 2,588 `Not Given` values retained in `director`.
- 287 `Not Given` values retained in `country`.
- `date_added` converted from text to datetime.
- Cleaned data exported as `cleaned_netflix.csv`.

## Skills demonstrated

- Data inspection with pandas
- Missing-value investigation
- Duplicate checking
- Data type conversion
- Text standardization
- Validation and before/after comparison
- CSV export

## Tools

- Python
- Jupyter Notebook
- pandas

## Project files

- `Netflix_Data_Cleaning.ipynb` — documented cleaning workflow and saved results.
- `Netflix1.csv` — source dataset used by the notebook.
- `cleaned_netflix.csv` — generated when the notebook is run.

## Run the notebook

1. Install Python and Jupyter Notebook.
2. Install pandas:

   ```bash
   pip install pandas
