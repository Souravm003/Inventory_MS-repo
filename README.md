# Inventory Management System Requirements (Require Documentation)
Design an Inventory Management System to keep track of all products, vendors, customers and orders. 
The system should be able to track what products are present in the inventory and what their current quantity is. 
Whenever we sell products to our customers, we should record the details in our system. If we are running out of stock of any product, 
we should be able to place an order for that product through one of the registered vendors.

We should track each product’s ID, name, category, sales price, cost, quantity and whether that product is active or not 
(i.e., whether we are currently selling that product or not, or if it may be out of stock). 
We should be able to calculate how much profit we are making by selling that product based on its cost and sales price. 
We can make that product active or inactive, or check whether that product is below the threshold or not. The threshold limit for each product is 100.

For each vendor and customer, we should keep a record of their contact details (name, phone number and email ID) and address details (street, city and state).
We should be able to get the contact and address details of any customer or vendor, or update their details whenever required.

For customers, we should also keep track of the number of transactions made within a period of time to identify frequent buyers and provide discounts 
to them accordingly. We should be able to get the total number of transactions made by a customer and calculate the discount.

For vendors, the system should be able to track their name (or their company’s name), the credit amount owed to them and the list of all the products sold by them. 
In addition, we should be able to check the credit owed to the vendor. The system should also allow us to check the details of the products sold by the vendor.
We should be able to look for a product based on the product ID or product name.

If we run out of stock (if the product is below the threshold), we should be able to place an order for those products with one of the registered vendors. 
For each order, we should be able to track its ID, details of the selected vendor, date of when the order is placed, the product ordered, 
the quantity ordered and the amount paid. If we place an order and do not pay the vendor, 
we should be able to update the credit balance (due amount) for that vendor.
