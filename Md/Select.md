# SELECT Statement.

To select specific Colum (DATA) from table use this syntex.

```sql
SELECT Colum1, Colum2 FROM Customers;
```

To understand better Think as Colum1, Colum2 Is a Country Colum and City Colum.


# Use Of *

Is used to select all colums (DATA) form customers table. LIKE ->

```sql
 SELECT * FROM Customers
 ```

# Use DISTINCT

In many cases we have a similar data like in 
Country colum we have 2 same country names and we want only one names then we'll use DISTINCT. LIKE ->

* SELECT DISTINCT Colum FROM Customers.

# Count Statement
The following SQL statement counts and returns the number of different (distinct) countries in the "Customers" table:

```sql
SELECT COUNT(DISTINCT Country) FROM Customers;
```
