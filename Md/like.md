# LIKE
The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.

* For Search Alfhabaticallt from starting Use :-
## Syntax
```sql
SELECT * FROM Cutomers WHERE City LIKE 'a%';
```
## LIKE to search second r word Use :-
```sql
SELECT * FROM Customers WHERE City Like '_r%';
```
## To find Name which is starting with a and ends with o Use :-
```sql
SELECT * FROM Customers WHERE City Like 'a%o';
```