# Excel
## Pivot Table
A pivot table in Excel is a powerful tool for summarizing and analyzing data. it is flexible as compare to normal tool.
## lookups
VLOOKUP, HLOOKUP, and XLOOKUP are Excel functions used to search for specific info. and retrieve data from a table or range.  
1)Vlookup : it is used for datasets with has vertical headlines. it searches for the value in leftmost column from the table and returns the corresponding value for a specif column to the right  
```excel
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])
```
2)Hlookup : It is used for datasets with has horizontal headlines. it searches for a value in the top row of a table and returns a corresponding value from a specified row below it.  
```excel
=HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])
```
3)XLookup : is a more  powerful function introduced in newer versions of Excel . It allows you to perform both vertical and horizontal lookups as well as handle multiple lookup conditions.
```excel
=XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode])
```
## Index function 
The INDEX function in Excel is a function used to retrieve a specific value from a range of cells in a worksheet. 
1) Syntax for a 1D dataset:
```excel
=INDEX(array, row_number)
```  
array: The range of cells (column or row) from which you want to retrieve a value.  
row_number: The row number (or index) specifying which value you want to retrieve.  
2) Syntax for a 2D dataset:
```excel
=INDEX(array, row_number, column_number)
```  
