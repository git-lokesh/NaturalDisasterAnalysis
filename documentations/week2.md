# Week 2: Data Cleaning – Customer Call Data

## Power BI (Power Query)

- Loaded customer call dataset into Power BI  
- Reviewed customer-related fields (names, phone numbers, addresses, flags)  
- Removed unnecessary and non-analytical columns  
- Standardized column names for clarity and consistency  
- Handled missing and invalid values (N/a, blanks → null)  
- Cleaned text fields using **Trim** and **Clean**  
- Standardized categorical values (Yes/No, Y/N)  
- Corrected data types for numeric and text columns  
- Removed duplicate customer records using unique IDs  
- Applied basic conditional filtering for valid contact records  

## Python (Jupyter Notebook)

- Loaded the dataset using **Pandas** in Jupyter Notebook  
- Inspected data using `info()` and `isnull()`  
- Revalidated missing values based on business relevance  
- Removed redundant and identifier columns programmatically  
- Converted data types explicitly to avoid calculation issues  
- Standardized categorical values across records  
- Validated numeric columns for accuracy  
- Exported the cleaned dataset for further analysis and reporting