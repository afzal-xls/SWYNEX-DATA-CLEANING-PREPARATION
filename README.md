# CAFE SALES DATA CLEANING

**Dataset: ** cafe sales-Dirty Data for cleaning Training (Kaggle)

**Tool used: ** Microsoft Excel

**Rows before:**10,000

**Rows after:**9,972

## Issues found and fixes

_**Missing values (numeric):**quantity, price and total were recalculated using total = quantity*price. 28 rows with 2 or more missing values were removed.
_**Missing /invalid text: **"ERROR","UNKNOWN" and blanks were replaced with "unknown"(item:966,payment Method:3,168,location:3949).
_**inconsistent values: **Extra spaces and mixed casing fixe (TRIM,PROPER).
_**incorrect data types: ** Dates stored as text (dd-mm-yy) and real dates were converted to one date format .
_**Missing dates: ** 458 left blank (not guesses).
_**Duplicates:** 0 duplicate Transaction IDs found.


## Files 

_raw_data.csv-original data 
-afzal.xlsx-cleaned data + cleaning log sheet
-README.md-this file
