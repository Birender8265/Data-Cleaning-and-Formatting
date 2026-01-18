# Data-Cleaning-and-Formatting

1. Dataset Download & Import

Downloaded dataset from Kaggle.
Opened CSV file in Microsoft Excel.
Verified that:
Column headers are correctly recognized.
Data is properly separated into columns.

2. Freeze Header & Apply Filters

Used View → Freeze Top Row to lock headers.
Applied filters using:
Data → Filter
This helped in easy data exploration.

3. Identify Missing Values

Used filter dropdown → selected (Blanks).
Highlighted missing values using:
Conditional Formatting
Based on column importance:
Filled missing values
Or removed unnecessary rows.

4. Remove Duplicates

Created a backup copy of raw data sheet.
Used:
Data → Remove Duplicates
Selected key columns (ID / Title).
Removed duplicate records safely.

5. Clean Text Data

Used Excel formulas:
=TRIM() → Remove extra spaces
=PROPER() → Capitalize first letters
=UPPER() → Convert to uppercase
After cleaning:
Copied values
Used Paste Special → Values

6. Fix Data Formats

Date columns:
Converted into YYYY-MM-DD format
Numeric columns:
Removed symbols (₹, $, %)
Converted to numbers.

7. Validate Categories

Standardized:
Country names
Ratings
Genres
Fixed spelling variations.

8. Create Cleaned Sheet

Created new sheet named:
Cleaned_Data
Copied cleaned data to this sheet.
Kept raw data unchanged.

9. Add Data Quality Notes

Added new column:
Data_Quality_Notes
Added remarks like:
"Missing director name"
"Duplicate removed"
"Rating inconsistent"
