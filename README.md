#  Residential Inventory Management System (RIMS)
A Course-Based Project (CBP) for the **Database Management Systems Laboratory** course.



## Project Overview
The **Residential Inventory Management System (RIMS)** is designed to manage properties, users, bookings, and payments in a structured and efficient way.  
It replaces manual management with a SQL-based relational database that ensures data accuracy, integrity, and easy retrieval.

This project demonstrates how **DBMS concepts** like normalization, ER modeling, keys, relationships, and SQL queries are applied to real-world scenarios.



##  Features
- Admin and User modules  
- Property listing and availability management  
- Booking and cancellation system  
- Payment tracking with status updates  
- Feedback and rating functionality  
- Referential integrity through foreign keys  
- Scalable design supporting future NoSQL integration


##  Database Design
**Entities:**
- Admin  
- User  
- Property  
- Booking  
- Payment  
- Resident  
- Feedback  

**Core DBMS Concepts Used:**
- Entity–Relationship (ER) Modeling  
- Normalization (1NF, 2NF, 3NF)  
- Primary and Foreign Keys  
- Constraints and Relationships  
- SQL Joins, Aggregate Functions, and Subqueries



##  Technologies Used
- **Database:** MySQL  
- **Language:** SQL  
- **Environment:** MySQL Workbench / Command Line  
- **Type:** Course-Based Project (CBP)



##  Sample Queries
- View available properties  
- Book or cancel a property  
- Record payments automatically after booking  
- Generate reports for total bookings or revenue  
- View feedback and user history  


##  Data Source
The dataset was **randomly generated using SQL functions** (`RAND()` and `INFORMATION_SCHEMA.TABLES`) to simulate real-world data.  
This approach allowed us to test scalability, constraint handling, and data relationships in a realistic environment.



##  Normalization Summary
1. **1NF:** Removed repeating groups and ensured atomic values.  
2. **2NF:** Eliminated partial dependencies on composite keys.  
3. **3NF:** Removed transitive dependencies for full data consistency.



##  Future Enhancements
- Web-based front-end for live property management  
- Integration with **NoSQL** databases for analytics  
- Role-based authentication and reports dashboard  



##  Authors
- Karthika Hanumandla 
- Jahnavi Dhulipati 
- Jeevana Harshini Mukku 
- Goutami Nurchu 