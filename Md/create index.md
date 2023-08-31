# CREATE INDEX STATEMENT.
The CREATE INDEX statement is used to create indexes in tables.

## CREATE INDEX Syntax
```sql
 CREATE INDEX Person ON Customers (LastName)
```
* If you want to create an index on a combination of columns, you can list the column names within the parentheses, separated by commas:
```sql
CREATE INDEX Person ON Customers (Lastname,Id)
```

## DROP INDEX
```sql
DROP INDEX Person ON Cutomers
