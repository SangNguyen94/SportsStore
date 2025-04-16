# SportsStore

This project is a web-based e-commerce application simulating an online sports equipment store. It is built using the ASP.NET MVC framework with C# and utilizes Microsoft SQL Server for data persistence via Entity Framework (Core). The application includes features for customers to browse products, manage their cart, place orders, and features for administrators/employees to manage products, orders, and potentially users.

---

## Features

**Customer Facing:**

* **Product Catalog:** Browse products by category, search, view product details.
* **Shopping Cart:** Add products to cart, update quantities, remove items.
* **User Accounts:** Registration and Login for customers.
* **Checkout Process:** Enter shipping details, review order (payment integration is likely a placeholder/mock).
* **Order History:** View past orders and their status.

**Admin / Employee Facing (requires login with appropriate role):**

* **Product Management:** Create, Read, Update, Delete (CRUD) operations for products and categories.
* **Order Management:** View customer orders, update order status (e.g., Shipped, Processing, Delivered).
* **Employee/User Management:** Manage users with administrative or employee roles. *(Optional: Depending on implementation)*
* 
## Technology Stack

* **Framework:** ASP.NET MVC 
* **Language:** C#
* **Database:** Microsoft SQL Server
* **ORM:** Entity Framework Core
* **Frontend:** HTML5, CSS3, JavaScript
* **Authentication:** ASP.NET Identity
* **Development Environment:** Visual Studio 2029 (*Recommended*)
