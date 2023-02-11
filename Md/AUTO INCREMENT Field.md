# AUTO INCREMENT Field
Auto-increment allows a unique number to be generated automatically when a new record is inserted into a table.

## Syntax

```sql
CREATE TABLE Person (
    FirstName varchar(255) UNIQUE,
    LastName varchar(255) NOT NULL UNIQUE,
    Id int not null auto_increment
);

```
## To let the AUTO_INCREMENT sequence start with another value, use the following SQL statement:

```sql
ALTER TABLE Person auto_increment=100;
```