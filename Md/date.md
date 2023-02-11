# DATES
comes with the following data types for storing a date or a date/time value in the database:

## Date Data Types.
```SQL
* `DATE` - format YYYY-MM-DD
* `DATETIME` - format: YYYY-MM-DD HH:MI:SS
* `TIMESTAMP` - format: YYYY-MM-DD HH:MI:SS
* `YEAR` - format YYYY or YY
```
Now we want to select the records with an OrderDate of "2008-11-11" from the table above.
```sql
SELECT * FROM Person WHERE OrderDate ='2008-11-11';
```