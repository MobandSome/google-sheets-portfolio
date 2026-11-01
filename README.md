# Google Sheets Data Analysis Portfolio

Spreadsheet projects showing how I clean, combine, look up, and summarize data in Google Sheets.

**Mohamed Adio** · B.A. Computer Science & Economics, Franklin & Marshall College

Each project folder has the original workbook (`.xlsx`, with formulas intact) and a `.csv` export of every tab so you can preview the data right here on GitHub.

## Projects

| Project | Data | Skills |
|---|---|---|
| [Boba tea data cleaning](data-cleaning-boba-tea) | ~600 Bay Area boba shops (name, rating, address, city, coordinates) | Cleaning raw data with spreadsheet functions: splitting a combined `lat-long` field into separate columns, removing empty columns |
| [Cleaning spreadsheets](cleaning-spreadsheets) | Order records | Spotting and fixing missing values and inconsistent formatting |
| [Combining data with CONCAT](concat-combining-data) | U.S. presidents' names and inauguration dates | `CONCAT`-style formulas to build full names and full dates from separate columns |
| [VLOOKUP employee pay](vlookup-employee-pay) | Daily hours worked plus an employee pay-rate table | `VLOOKUP` across sheets, handling messy name spacing, pivot table of total pay per employee |
| [Conditional formulas: sales](conditional-formulas-sales) | Sales reps by state, clients, and sales | Conditional logic, average sales per client, commission calculations |
| [Movie pivot tables](pivot-tables-movies) | ~500 films with genre, director, cast, budget, box office | Pivot tables by director and genre, average budget vs. revenue, calculated profit field |

## Datasets

Raw datasets used for practice, in [`datasets/`](datasets):

- `automobile_data` – 200+ cars with make, fuel type, body style, engine specs, mpg, and price
- `student_performance_data` – ~650 student records with demographics, study time, and grades

## Tools

Google Sheets: formulas, data cleaning functions, pivot tables, sorting and filtering.
