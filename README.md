# Second_Excel
# Gradebook Assignment

An Excel workbook that tracks test scores for 17 employees across four required tests and flags anyone who fails.

## File

- `Gradebook.xlsx`

## What it does

- **Test scores**: raw points for Safety Test, Company Philosophy Test, Financial Skills Test, and Drug Test, out of the possible points listed in row 2
- **Percentage columns**: each test score converted to a percentage with `=score/points possible`
- **Fire Employee**: flags `TRUE` if an employee scored below 50% on any of the four tests, using `OR(...)`
- Summary rows for Max, Min, and Average across all employees, for both raw scores and percentages

## Notes

- Trent Mann's Safety Test score (11 out of 10 possible) is intentional and not a data error.
