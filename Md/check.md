# CHECK
The CHECK constraint is used to limit the value range that can be placed in a column..

## CHECK on CREATE TABLE.
```sql
CREATE TABLE Persons (
    ID int NOT NULL,
    LastName varchar(255) NOT NULL,
    FirstName varchar(255),
    Age int,
    CHECK (Age>=18)
);

```
## CHECK on ALTER TABLE.
```sql
ALTER TABLE Orders ADD CHECK (Age>= 18);

```
* To allow naming of a CHECK constraint, and for defining a CHECK constraint on multiple columns, use the following SQL syntax:
```sql
ALTER TABLE Customers ADD CONSTRAINT C_PersonAge CHECK (Age >= 18 AND City='Sandnes');

```
## DROP a CHECK Constraint.
```sql
1. ALTER TABLE Customers DROP CONSTRAINT C_PersonAGe;
2. ALTER TABLE Customers DROP CHECK C_PersonAge;

```