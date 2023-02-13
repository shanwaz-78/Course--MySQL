# ALIASES
* SQL aliases are used to give a table, or a column in a table, a temporary name.
* Aliases are often used to make column names more readable.
* An alias only exists for the duration of that query.
* An alias is created with the AS keyword.

## Alias for Columns 
```sql
SELECT CustomerName AS Customer, ContactName AS Contacts FROM Customers;
```

## Alias with combine
```sql
SELECT CustomerName, Address + ' ' + ContactName + ' ' + PostalCode AS Combine FROM Customers;
```