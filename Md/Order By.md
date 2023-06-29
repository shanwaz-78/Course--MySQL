# ORDER BY.
It's used to sort the result in ascending or descending order.  ascending is by default and descending is manually. LIKE ->

SELCET * FROM Customers ORDER BY Country. (Ascending)
```sql
SELECT * FROM Products ORDER BY Country DESC. (Descending)
```
## Several Colums.
```sql
SELECT * FROM Products ORDER BY CustomerName, Country.
```
## ORDER BY Several Columns Example 2.
```sql
SELECT * FROM Customers ORDER BY CountryName ASC, CustomerName DESC.
```
