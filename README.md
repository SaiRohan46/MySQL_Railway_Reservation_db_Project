# MySQL_Railway_Reservation_db_Project
A MySQL-based Railway Reservation System that manages passengers, trains, stations, routes, coaches, bookings, tickets, and payments. Features a normalized relational database, ER diagram, sample data, and 30+ SQL queries ranging from basic operations to advanced joins, aggregations, and subqueries, demonstrating practical DBMS concepts.
## Project Overview
The Railway Reservation System is a MySQL database project designed to manage trains, passengers,
stations, routes, bookings, tickets, coaches, and payments.

This project demonstrates:
- Database creation
- Relational database design
- Primary and Foreign Keys
- SQL query implementation
- Real-world railway reservation workflow

## Technologies Used
- MySQL
- SQL

## Database Tables
1. Passenger
2. Train
3. Station
4. Route
5. Coach
6. Booking
7. Ticket
8. Payment

## Relationships
- One train has many coaches.
- One train follows many route entries.
- One passenger can have many bookings.
- One booking generates one ticket and one payment.

## SQL Queries Included
- Easy Queries (10)
- Intermediate Queries (10)
- Hard Queries (10)

## Features
- Train management
- Passenger management
- Booking system
- Ticket generation
- Payment tracking
- Route management

## Learning Outcomes
- Relational database concepts
- SQL joins
- Aggregate functions
- Grouping and filtering
- Database normalization

| **Team Member** | **Contribution**                                                                                                                                                                                                                                                                                                                                  |
| --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rohan**       | Led the project by designing the complete database schema, creating all SQL tables, defining primary and foreign key relationships, implementing constraints, inserting sample data, and developing Easy and Intermediate SQL queries. Coordinated database integration and ensured proper normalization and data consistency across all modules. |
| **Kavya**       | Developed the Railway Reservation database structure, implemented Booking, Ticket, Coach, and Payment modules, created advanced SQL queries using JOINs, GROUP BY, HAVING, and aggregate functions, assisted in testing, validated query outputs, optimized SQL queries, and prepared the project documentation and README.                                              |
| **Abhinav**     | Designed the ER diagram, verified relationships between entities, tested database integrity, reviewed project implementation, and assisted in debugging, validation, and final project presentation.                                                                                                                       |
