# Create Table.
The CREATE TABLE statement is used to create a new table in a database.

## Syntax
```javascript
CREATE TABLE table_name (
    column1 datatype,
    column2 datatype,
    column3 datatype,
   ....
);

```
## Create Table Using Another Table.
```javascript
CREATE TABLE new_table_name AS
    SELECT column1, column2,...
    FROM existing_table_name

```