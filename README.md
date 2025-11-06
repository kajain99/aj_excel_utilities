# AJ excel Utlities ( Free Excel & CSV Utility Tools) 

A free, lightweight desktop toolkit built in Python to make Excel and CSV tasks faster and easier — all running locally with no data upload.

## Features

### Easy VLOOKUP
Join two Excel or CSV files instantly, just like Excel’s `VLOOKUP()` function but simpler.  
Select your **Destination file** (the one you want to enrich) and your **Source file** (the one providing extra columns).  
One click and the lookup is done.

### Multi-Key VLOOKUP
Perform lookups using two keys (for example, *Name + City* when the name is not unique).  
A live preview lets you confirm before merging.

### Cleaning Tools
Trim spaces (like Excel’s `TRIM()`), remove duplicates, fix numbers saved as text, and remove empty rows or columns.

### Batch Cleanup
Select multiple sheets, apply multiple cleaning actions, and process all your files in one go.

### Column Reorder/Delete
Rearrange columns using simple arrow buttons or delete unwanted ones with a cross, instead of manually cutting and pasting.

### Simple Merge
Stack multiple files vertically into one dataset — perfect for merging monthly or departmental reports.  
All selected files should have the same columns (use Column Reorder first if needed).

### Regex Replace
Search and replace text using regular expressions (regex).  
Use templates for common patterns such as digits, emails, URLs, or capitalized words.  
Preview results before applying to multiple columns.

## Built With

- **Python**
- **PySide6** – for the Windows GUI  
- **pandas** – for all data operations  
- **python-calamine**, **openpyxl**, **XlsxWriter** – for file import/export  
- **chardet** – to detect CSV encoding  
- **re (Regular Expressions)** – for advanced text replacements

## Notes

All processing happens locally on your computer.  
No internet connection or data upload is required.
