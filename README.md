# powerquery
A collection of functions written in Power Query (M)
*Or "I paste stuff here sometimes"*


## What you'll find:

## Table Manipulation
| Function | Description |
| :--- | ----------- |
| [Table.ReplaceValuesFromTable](Tables/Table.ReplaceValuesFromTable.pq) | Ever wanted to mass replace values in columns? This is optimised to do exactly that. |
| [Table.CombineMultipleColumns](Tables/Table.CombineMultipleColumns.pq) | For the pain of excel files with double headers. Combine columns by any setSize in one step. |
| [Table.GenerateColumns](Tables/Table.GenerateColumns.pq) | To add multiple columns based on similar functions. If you think you need this, have you thought about just unpivoting and adding one column afterwards? |


## Time Intelligence
| Function | Description |
| :--- | ----------- |
| [DateTime.Diff](Time Intelligence/DateTime.Diff.pq) | DateTime Diff using 'Excluded Dates' list and 'Start Time' / 'End Time'. |
| [Date.Diff](Time Intelligence/Date.Diff.pq) | Date Diff using 'Excluded Dates' list. |
| [Duration.To](Time Intelligence/Duration.To.pq) | All Duration.TotalXXXX functions in one. |
