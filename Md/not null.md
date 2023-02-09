# NOT NULL
It's Mean The NOT NULL constraint enforces a column to NOT accept NULL values.

## Syntax
```sql
CREATE TABLE Persons (
    ID int NOT NULL,
    LastName varchar(255) NOT NULL,
    FirstName varchar(255) NOT NULL,
    Age int
);

```
## SQL NOT NULL on ALTER TABLE
```sql
ALTER TABLE Persons
ALTER COLUMN Age int NOT NULL;

```