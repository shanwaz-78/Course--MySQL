# LEFT JOIN
The LEFT JOIN keyword returns all records from the left table (table1), and the matching records from the right table (table2). The result is 0 records from the right side, if there is no match.

## Left Join Syntax.
```sql
SELECT Customers.CId, Customers.CName, Orders.Oid 
FROM Customers LEFT JOIN Orders
ON Customers.CId = Orders.Oid;
```
![Left Join](https://www.w3schools.com/sql/img_leftjoin.gif)