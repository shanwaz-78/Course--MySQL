# UNIQUE
The UNIQUE constraint ensures that all values in a column are different.

* A PRIMARY KEY constraint automatically has a UNIQUE constraint.

## Syntax.
```sql
CREATE TABLE Persons (
    ID int NOT NULL UNIQUE,
    LastName varchar(255) NOT NULL,
    FirstName varchar(255),
    Age int
);

```
## UNIQUE Constraint on ALTER TABLE.
```sql
ALTER TABLE Persons
ADD UNIQUE (ID);

``` 
## Remove Constraint.
```sql
ALTER TABLE Information DROP CONSTRAINT Id

```