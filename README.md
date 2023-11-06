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
## MATCH function  
 MATCH function is used to find the relative position of a specified value within a range of cells.  
 ```EXCEL
=MATCH(lookup_value, lookup_array, [match_type])
```

## String Function 
1)CONCATENATE (or CONCAT):

Combines two or more strings into a single string.
Syntax:
```excel
=CONCATENATE(text1, text2, ...)
```
Example:
```excel
=CONCATENATE("Hello, ", "World!") or =CONCAT("Hello, ", "World!")
```

2)LEN:

Returns the length (number of characters) of a text string.
```excel
=LEN(text)
```
Example:
```excel
=LEN("Excel") returns 5
```
3)LEFT:

Returns a specified number of characters from the beginning of a text string.
Syntax:
```excel
=LEFT(text, num_characters)
```
example  
```excel
=LEFT("Excel Functions", 5) returns "Excel"
```
4)RIGHT:
Returns a specified number of characters from the end of a text string.  
Syntax: 
```excel
=RIGHT(text, num_characters)
```
Example:
```excel
=RIGHT("Excel Functions", 9) returns "Functions"
```
5)MID:
Returns a specified number of characters from a text string, starting at a specific position.
Syntax:
```excel
=MID(text, start_position, num_characters)
```
Example:
```excel
=MID("Excel Functions", 7, 9) returns "Functions"
```
6)FIND:
Returns the position of a specified substring within a text string.
Syntax:
```excel
=FIND(find_text, text, [start_num])
```
Example:
```excel
=FIND("World", "Hello, World!") returns 7
```

7)SUBSTITUTE:
Replaces occurrences of a substring with a new substring within a text string.
Syntax:
```excel
=SUBSTITUTE(text, old_text, new_text, [instance_num])
```
Example:
```excel
=SUBSTITUTE("Hello, World!", "World", "Excel") returns "Hello, Excel!"
```

8)UPPER and LOWER:
Convert text to all uppercase or all lowercase, respectively.
Syntax:
```excel
=UPPER(text) and =LOWER(text)
```
Example:
```excel
=UPPER("excel") returns "EXCEL" and =LOWER("EXCEL") returns "excel"
```
## insert comment
right click and insert comment  
## slicer
used for doing filter ooperation in efficient way.  
it basically gives the values of diff. fields in form of slices  
## texttocolumn
present in data tab
