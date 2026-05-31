Netflix Dataset – Data Cleaning Summary

This document explains the data cleaning steps performed on the Netflix Titles dataset.

Steps Performed
Created a table for the full dataset for easy analysis
Auto-adjusted column width and height for better readability
Checked for duplicates and confirmed there are no duplicate records
Found missing values in the Director column and replaced them with "UNKNOWN"
In the Cast column, missing values were replaced with "Not Available"
In the Country column, blank values were found using filters and replaced with "UNKNOWN"
In the Rating column, missing values were replaced with "Not Rated"
In the Duration column, blank values were replaced with "Unknown" using find and replace
Removed extra spaces from all important columns such as:
Title
Director
Cast
Country
Rating
Listed_in
Description
Corrected the data type of the date column to proper date format
Created two new columns:
Duration_Number (numeric part of duration)
Duration_Type (minutes or seasons)
Verified all columns for correct and consistent data types
Conclusion

The dataset is now clean.
