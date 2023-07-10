# UPDATE.
Update statment is used to modify the existing records in table. LIKE->

```sql
UPDATE Customers SET Country = 'mexico', City = 'London' WHERE CustomerId = 1;
```


## Change the all data's PostalCode.
```sql
 UPDATE Customers SET PostalCode = 0000
```

## Change the specific data PostalCode.
```sql
 UPDATE Customers SET PostalCode = 0000 WHERE Country = 'mexico';
```
