# Sample Exercise: Finding High-Value Customers of Differing Ages

You're working for an e-commerce company, and you've been tasked with identifying high-value customers from younger and older demographics, to determine which demographic to target with enhanced marketing. 

You have a "customers" table with information about each customer, including their total spending and ages (in the total_spent and customer_age columns respectively). Your manager wants a list of customers who have spent more than $1000. Let's use the WHERE clause to filter the data and find these valuable customers! 

## Instructions:

A) Write a SQL query to select the "customer_id" and "name" from the "customers" table.

B) Use the WHERE clause to filter for high value customers (whose total_spent is greater than 1000).

C) Add an AND clause to filter for high value customers aged less than 25 (whose customer_age < 25 yrs).

D) Add an AND clause to filter for high value customers aged more than 35 yrs (whose customer_age > 35 yrs).

E) Should your e-commerce company target high value clients of an older or younger demographic? Why?

Sample Code:

SELECT ___________, ____  -- Select the customer ID and name
FROM _________ -- From the customers table
WHERE ___________ > ____; -- Filter for high-value customers

## Solution Code:

A) SELECT customer_id, name 
FROM customers

B) SELECT customer_id, name 
FROM customers
WHERE total_spent > 1000; 

C) SELECT customer_id, name 
FROM customers
WHERE total_spent > 1000
AND customer_age < 25; 

D) SELECT customer_id, name 
FROM customers
WHERE total_spent > 1000
AND customer_age > 35; 