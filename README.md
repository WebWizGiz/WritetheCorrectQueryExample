# WritetheCorrectQueryExample
Write the correct Query to accomplish these tasks
Exercise 1: Create the Pizza Orders Table
Create a table named `PizzaOrders` that will store information about orders placed by customers. The table should have the following columns:
- `OrderID` (int)
- `CustomerName` (varchar(255))
- `PizzaType` (varchar(255))
- `Quantity` (int)
- `OrderAddress` (varchar(255))
- `City` (varchar(255))
- `PostalCode` (int)
- `Country` (varchar(255))

 Exercise 2: Insert Sample Data
Insert the following orders into the `PizzaOrders` table:
1. Order ID: 1, Customer Name: 'John Smith', Pizza Type: 'Margherita', Quantity: 2, Order Address: '123 Main St', City: 'Berlin', Postal Code: 10115, Country: 'Germany'
2. Order ID: 2, Customer Name: 'Maria Garcia', Pizza Type: 'Pepperoni', Quantity: 1, Order Address: '456 Elm St', City: 'Munich', Postal Code: 80331, Country: 'Germany'
3. Order ID: 3, Customer Name: 'Ahmed Zayat', Pizza Type: 'Veggie', Quantity: 3, Order Address: '789 Pine St', City: 'Frankfurt', Postal Code: 60313, Country: 'Germany'
4. Order ID: 4, Customer Name: 'Liu Wei', Pizza Type: 'Hawaiian', Quantity: 2, Order Address: '321 Oak St', City: 'Hamburg', Postal Code: 20095, Country: 'Germany'

 Exercise 3: Retrieve All Orders
Write a SQL query to select all columns from the `PizzaOrders` table.

 Exercise 4: Find Unique Cities
Write a SQL query to find all the distinct cities where orders have been placed.

  Exercise 5: Sort Orders by Quantity
Write two SQL queries to select all columns from the `PizzaOrders` table and sort the results by `Quantity` in ascending and then in descending order.

 Exercise 6: Filter Orders from Germany
Write a SQL query to select all orders from the `PizzaOrders` table where the country is 'Germany'. Order the results by `CustomerName`.

 Exercise 7: Filter and Sort Specific Orders
Write a SQL query to select all orders from the `PizzaOrders` table where the country is 'Germany' and the `CustomerName` starts with 'M'. Order the results by `CustomerName` in descending order.

  Exercise 8: Handling Typographical Errors in Country Names
Assuming there was a typo in some entries where 'Germany' was misspelled as 'Germnay', write a SQL query to select all orders from the `PizzaOrders` table where the country is either 'Germany' or 'Germnay'.
