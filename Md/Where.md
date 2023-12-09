# WHERE
The WHERE is used to filter records. Like we want to see only mexico country customers. the we'll write.->

```sql
SELECT * FROM Customers WHERE Country='mexico'
```
# Text Field Vs Numeric Field.

SQL requires single quotes around text values (most database systems will also allow double quotes). To See Customers data by id write ->

```sql
SELECT * FROM Customers WHERE CustomerId = 2
```

# BETWEEN Statement.

BETWEEN Statement is used to find data in a range.

```sql
SELECT * FROM Products WHERE Price BETWEEN 20 AND 30
```

# Like Statement.

LIKE Statement is used to find data Alphabet Wise.

```sql
SELECT * FROM Products WHERE City LIKE 'b%'
```

# IN Statement.

To Check data from city wise then use IN.

```sql
SELECT * FROM Customers WHERE City IN ('Paris','London')
```

# NOT Statement.

Not is used to check the specific city record that is whether exist or not.

```sql
 SELECT * FROM Customers WHERE NOT City = 'Berlin';
```
