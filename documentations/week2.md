# Week 2: Data Cleaning – Customer Call Data

## Power BI (Power Query)

- Imported customer call dataset into Power BI  
- Focused on **data quality issues** in raw customer data  
- Removed unnecessary and non-analytical columns  
- Renamed columns for clarity and business readability  
- Handled missing and invalid values (N/a, blanks → null)  
- Cleaned text fields using **Trim** and **Clean**  
- Standardized categorical values (Yes/No, Y/N)  
- Corrected data types for IDs, text, and flags  
- Removed duplicate customer records using unique identifiers  
- Applied basic business rules for valid contact data  

## Python (Jupyter Notebook)

- Loaded cleaned data using **Pandas**  
- Performed validation checks using `info()` and `isnull()`  
- Ensured consistency between Power BI and Python-cleaned data  
- Converted data types programmatically  
- Exported the finalized clean dataset for analysis