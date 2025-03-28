**Restaurant Ordering System API** 
This project implements a Restaurant Ordering System using ASP.NET Core and Orleans, designed to manage restaurant orders and their statuses through a web API. The system allows the creation of orders, fetching of orders by their ID, and updating the status of orders. It integrates with DynamoDB for persistent storage and Orleans for distributed, fault-tolerant state management.

Features
Create Order: Allows clients to create a new order with a unique order ID.
Get Order: Fetches an order's details based on its order ID.
Update Order Status: Updates the status of an existing order (e.g., "Pending", "In Progress", "Completed").
Integration with Orleans Grains: Leverages Orleans' virtual actor model for state management and distributed computations.
Persistence with DynamoDB: Orders and their statuses are saved to DynamoDB for durability.

Technologies
ASP.NET Core: Used for building the RESTful API.
Orleans: A distributed framework used for managing and processing order data.
DynamoDB: A NoSQL database used to store order details and their statuses.
