# Assignment_1_MUTABOBA_Elois-2025SEN241

Hello, welcome to my first assignment. The case study we have today is SunriseSupermarket, Sunrise Supermarket sells products to customers, who place orders containing one or more items. Management wants to understand who their customers are, what they buy, and how sales are trending over time. 

## Our first task in this project is to: 

Populate the tables with at least 5 customers, 8 products across at least 3 categories, 15 orders, and 25 order items across multiple dates. 

## Our second task is:

1. List every order with the customer's name, city, and order date (INNER JOIN: orders + customers).

2. List every order item with product name, category, price, and quantity (JOIN: order_items + products).

3. List all customers and their orders where they exist, including customers with no orders (LEFT JOIN: customers + orders).

4. Calculate each customer's total spend (quantity x price) and return customers above average spend. Use a CTE to compute customer totals first. (CTE QUERY).

5. Rank customers by total amount spent, highest first.

6. Number each customer's orders in the order placed.

7. Show a running total of revenue over time, ordered by order date.

8. For each customer with more than one order, show days between the current and previous order.

9. For each customer with more than one order, show days between the current and previous order.


## The tech stack being used: 

Oracle's Database SQL Developer extension in Vscode, and Docker image of Oracle XE. Reason for using the approach: I am currently using Kali linux i can't access a .deb file for Oracle XE (Doesn't exist only .rpm).
