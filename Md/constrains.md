# Constraints
Constraints is used to specify rules for data in table.

## Syntax.
```Javascript
CREATE TABLE table_name (
    column1 datatype constraint,
    column2 datatype constraint,
    column3 datatype constraint,
    ....
);

```
Constraints can be column level or table level. Column level constraints apply to a column, and table level constraints apply to the whole table.

* The following constraints are commonly used in SQL:

`NOT NULL` - Ensures that a column cannot have a NULL value<br>
`UNIQUE` - Ensures that all values in a column are different<br>
`PRIMARY KEY` - A combination of a NOT NULL and UNIQUE. Uniquely identifies each row in a table<br>
`FOREIGN KEY` - Prevents actions that would destroy links between tables<br>
`CHECK` - Ensures that the values in a column satisfies a specific condition<br>
`DEFAULT` - Sets a default value for a column if no value is specified<br>
`CREATE INDEX` - Used to create and retrieve data from the database very quickly<br>