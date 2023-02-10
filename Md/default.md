# DEFAULT Constraint
The DEFAULT constraint is used to set a default value for a column.

## DEFAULT on CREATE TABLE
```sql
CREATE TABLE Person (
    Id int NOT NULL auto_increment,
    FirstName VARCHAR(200),
    City VARCHAR(200) DEFAULT = 'Mexico'
);

```
## Default on ALTER TABLE
```sql
ALTER TABLE Person ALTER City SET DEFAULT = 'Mexico';

ALTER TABLE Person ALTER COLUMN City SET DEFAULT = 'Mexico';
```
## DROP a DEFAULT Constraint.
```sql
ALTER TABLE Person ALTER City DROP DEFAULT;
ALTER TABLE Person ALTER COLUMN City DROP DEFAULT;
```