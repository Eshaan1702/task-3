 1. Select all columns from Products
SELECT * FROM Products;

 2. Select specific columns from Customers
SELECT CustomerName, Address FROM Customers;

 3. Select products where price is greater than 500
SELECT * FROM Products
WHERE Price > 500;

 4. Select customers from a specific city using LIKE
SELECT * FROM Customers
WHERE Address LIKE '%Delhi%';

 5. Select orders between two specific dates
SELECT * FROM Orders
WHERE OrderDate BETWEEN '2024-01-01' AND '2024-12-31';

 6. Select products with stock between 10 and 50
SELECT * FROM Products
WHERE Stock BETWEEN 10 AND 50;

7. Select customers with name starting with 'A' or 'B'
SELECT * FROM Customers
WHERE CustomerName LIKE 'A%' OR CustomerName LIKE 'B%';

 8. Select orders sorted by OrderDate (descending)
SELECT * FROM Orders
ORDER BY OrderDate DESC;
 9. Select top 5 most expensive products
SELECT * FROM Products
ORDER BY Price DESC
LIMIT 5;

 10. Combine conditions with AND and OR
SELECT * FROM Products
WHERE Price > 100 AND Stock < 20 OR ProductName LIKE '%Book%';
