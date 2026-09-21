# Assignment_1_MUTABOBA_Elois-2025SEN241

Hello, welcome to my first assignment. The case study we have today is SunriseSupermarket, Sunrise Supermarket sells products to customers, who place orders containing one or more items. Management wants to understand who their customers are, what they buy, and how sales are trending over time. 

## Our first task in this project is to: 

Populate the tables with at least 5 customers, 8 products across at least 3 categories, 15 orders, and 25 order items across multiple dates. 

## Our second task is:

1. List every order with the customer's name, city, and order date (INNER JOIN: orders + customers). <img width="1088" height="737" alt="image" src="https://github.com/user-attachments/assets/9cdac2d2-e9bd-4a4e-a052-2969c4ebcd8c" />


2. List every order item with product name, category, price, and quantity (JOIN: order_items + products). <img width="1042" height="855" alt="image" src="https://github.com/user-attachments/assets/aa673cc1-6087-43ba-8b10-79d4717356a0" />


3. List all customers and their orders where they exist, including customers with no orders (LEFT JOIN: customers + orders). <img width="1108" height="915" alt="image" src="https://github.com/user-attachments/assets/738de044-13f0-46f0-9b1e-87231012994c" />


4. Calculate each customer's total spend (quantity x price) and return customers above average spend. Use a CTE to compute customer totals first. (CTE QUERY).  <img width="1108" height="915" alt="image" src="https://github.com/user-attachments/assets/13feb81b-9341-423d-9874-386cdf33fafa" />


5. Rank customers by total amount spent, highest first.  <img width="1108" height="915" alt="image" src="https://github.com/user-attachments/assets/564ad9b9-f42e-489d-b6f6-9577aa0e12e9" />


6. Number each customer's orders in the order placed. <img width="1108" height="915" alt="image" src="https://github.com/user-attachments/assets/27d63f03-d99c-40cc-8777-b6221159c0ba" />


7. Show a running total of revenue over time, ordered by order date.  <img width="1108" height="915" alt="image" src="https://github.com/user-attachments/assets/39eec492-8e45-427d-bcd4-0fd0256c35c0" />


8. For each customer with more than one order, show days between the current and previous order.  <img width="1108" height="915" alt="image" src="https://github.com/user-attachments/assets/83319e8f-f908-4b2c-9e86-b545fc153ab1" />




## The tech stack being used: 

Oracle's Database SQL Developer extension in Vscode, and Docker image of Oracle XE. Reason for using the approach: I am currently using Kali linux i can't access a .deb file for Oracle XE (Doesn't exist only .rpm).
