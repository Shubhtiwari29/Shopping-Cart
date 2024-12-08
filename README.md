## Features

• User Management: Register, login, and manage user profiles.
• Product Management: View and manage product catalog with categories.
• Cart Operations:
• Add items to the cart.
• Update cart item quantities.
• Remove items from the cart.
• Order Management: Place orders and view order history.
• Database Integration: Persistent storage of user, product, and order data using MySQL.
• Secure API: Secured endpoints with Spring Security.

## Technologies Used
• Backend:
1) Java
2) Spring Boot (MVC, Data JPA, Security)
3) Hibernate
• Database:
1) MySQL
   
• Build Tool:
Maven

API Endpoints
Endpoint	Method	Description
/api/users -	POST -	Register a new user
/api/products	- GET -	Get all products
/api/cart	- POST -	Add an item to the cart
/api/cart/{id}	- DELETE -	Remove an item from the cart
/api/orders	- POST	- Place an order
