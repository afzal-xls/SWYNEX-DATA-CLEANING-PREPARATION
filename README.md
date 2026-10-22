# Cafe Sales Data Cleaning

*Dataset:* Cafe Sales - Dirty Data for Cleaning Training (Kaggle)

*Tool used:* Microsoft Excel

*Rows before:* 10,000

*Rows after:* 9,972

## Issues found and fixes

- *Missing values (numeric):* Quantity, Price and Total were recalculated using Total = Quantity x Price. 28 rows with 2 or more missing values were removed.
- *Missing/invalid text:* "ERROR", "UNKNOWN" and blanks were replaced with "Unknown" (Item: 966, Payment Method: 3,168, Location: 3,949).
- *Inconsistent values:* Extra spaces and mixed casing fixed (TRIM, PROPER).
- *Incorrect data types:* Dates stored as text (dd-mm-yy) and real dates were converted to one date format.
- *Missing dates:* 458 left blank (not guessed).
- *Duplicates:* 0 duplicate Transaction IDs found.

## Files

- dirty_cafe_sales.xlsx.xlsx - original data
- cleaned_cafe_data_xlsx.xlsx- cleaned data + Cleaning Log sheet
- README.md - this file
