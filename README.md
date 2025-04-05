# Food-Delivery-Management-System

📦 Food Delivery Management System – Summary
This project is a fully structured SQL Server database for a Food Delivery Management System designed to manage users, orders, items, categories, offers, payments, and live tracking features. It serves as the backend foundation for a modern food delivery app.

🎯 Key Features
User & Role Management:
Supports user roles (admin, customer, driver) with a permission system.

Authentication & OTP:
Handles user verification, secure login, and one-time password fields.

Address System:
Users can store multiple delivery addresses, all located in Jordan.

Item & Category Management:
Organize food items under categories with multilingual support (English/Arabic).

Offers & Discounts:
Dynamic offers per category or item with start/end dates, limits, and codes.

Order Management:
Full order lifecycle tracking including order items, status, and customer ratings.

Payment System:
Tracks payments, methods, and statuses linked to each order.

Live Driver Tracking:
Added DriverLocation table to support live GPS tracking of drivers on a map.

Favorites & Notifications:
Users can favorite items and receive real-time notifications.

Tickets & Support:
Customers can open support tickets for issues or suggestions.

Chat System:
Real-time chat between customer and driver/support per order.

🛠 Technologies
Database: SQL Server

Data Types: Supports Arabic content via NVARCHAR

Constraints: All foreign keys and cascading behaviors handled

Indexes: Unique constraints to avoid duplicates

Real Data: Includes realistic sample data for users, addresses, items, etc., with addresses based in Jordan
