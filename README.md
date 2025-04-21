# Customer Personality Analysis

## Objective
To clean the `marketing_campaign.csv` dataset by addressing the following:
- Missing values
- Duplicate records
- Inconsistent column names
- Incorrect or inconsistent data types
- Standardization of text values
- Date formatting

## Steps Performed
1. **Loaded the CSV file** using pandas.
2. **Cleaned column names** to ensure lowercase and underscores.
3. **Handled missing values** using `.isnull()` and replaced as needed.
4. **Removed duplicate entries** using `.drop_duplicates()`.
5. **Standardized date format** for the `Dt_Customer` column.
6. **Standardized text values** for fields like `education` and `marital_status`.
7. **Converted data types** such as `income` to numeric and `dt_customer` to datetime.

## Output
A cleaned version of the dataset: `marketing_campaign_cleaned.csv`.

