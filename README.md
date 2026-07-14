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

## Authors

| **Team Member**       | **Contribution**                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Rohan** | Led the overall project development by designing the complete database architecture, creating SQL tables, defining primary and foreign key relationships, implementing constraints, developing Easy, Intermediate, and Advanced SQL queries, optimizing database performance, ensuring database normalization and data integrity, coordinating team activities, reviewing implementations, and preparing the final project documentation and README. |
| **Kavya**             | Developed the Passenger, Train, Station, Route, Booking, Ticket, Coach, and Payment modules, inserted realistic sample data, implemented database relationships, assisted in SQL query development, validated query outputs,ensuring database normalization and data integrity, coordinating team activities and contributed to debugging and successful integration of all project modules.                                                                                                             |
| **Abhinav**           | Designed the Entity-Relationship (ER) Diagram, verified relationships between database entities, reviewed SQL scripts for consistency, tested database integrity, assisted in debugging and validation, and supported the preparation of the final project report and presentation.                                                                                                                                                                  |

Conclusion

The Railway Reservation System successfully demonstrates the practical implementation of a relational database using MySQL. The project provides an efficient solution for managing passengers, trains, stations, routes, coaches, bookings, tickets, and payments through a well-structured and normalized database design. By implementing primary and foreign key relationships, the system ensures data integrity, minimizes redundancy, and maintains consistency across all interconnected tables.
