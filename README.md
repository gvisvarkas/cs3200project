# cs3200project

Problem Statement:
We are trying to create a model for an e-commerce store. Many small businesses find it difficult to share current and historical order information back to their customers, from the price to the ship date. While there are a variety of software, online tools and paper records businesses could utilize, with our e-commerce storefront, we help customers keep track of their information in a simplified manner. Our project not only simplifies the process of keeping track of records but it also establishes relationships between customers and their orders & products and their orders.

Solution Statement:
We are solving the problem by creating three tables: customers, orders, and products. We created two association classes: one between customers and products and one between orders and products. The one between customers and products represents the ratings/reviews for the products. The one between orders and products represents the order details for each product. Each of the tables and their association classes keeps track of information regarding orders such that customers are satisfied and informed.

User:
Because our goal is to ensure that shoppers of a store are able to view their orders/relevant information, the typical user would be a customer. The customer would use our solution to view their orders and the products ordered. The customer can view how much they paid, how much each product cost, and how many products they ordered.

Domain objects:
Order, and product. For the order domain object, we keep track of price, address, status, number of items, gift, and delivery date. For the product domain object, we keep track of name, category, seller name, posted date, and stock quantity.
