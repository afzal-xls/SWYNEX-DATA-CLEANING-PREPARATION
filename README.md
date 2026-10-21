# CAFE SALES DATA CLEANING

** Dataset ** cafe sales-Dirty data for Cleaning Training (Kaggle)
** Tool used: ** Microsoft excel
** Rows Before: ** 10,000| **Rows After: **,9,972

## Issues found and fixes
_**Missing values (numeric): ** Quantity, pricem total recalculated using total = Quantity*price, 28 rows with 2+missing values were removed
_**Missing/invalid text: ** "ERROR","UNKNWON" and blanks replaced with "unknwon" (Item: 966, Payment Method:3168, Location:3949).
_**inconsistent values:**Extra spaces and mixed casing fixed (TRIM, PROPER).
_**incorrect data types: ** Dates stored as text (dd-mm-yy) and real dates converted to one date format.
_**Missing dates :**458 left blank ( note guessed).
_**Duplicates :**0 duplicate Transaction IDs found.


## Files 
-raws_data.csv-original data
-afzal.xlsx - cleaned data + cleaning log sheet 
-README.md-this file
