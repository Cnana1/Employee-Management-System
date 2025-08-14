# employee-management-system

A Java-based console application that enables efficient management of employee records for small organizations (fewer than 20 employees).
This system supports CRUD operations, salary adjustments, and simple reporting directly from the terminal interface.

Features

Add / Update / Delete employee records

Search employees by:

Employee ID

Name

Social Security Number (SSN)

Apply bulk salary increases to all employees or selected groups

Generate basic reports for HR and payroll purposes

Data persistence with MySQL, JDBC, and HikariCP connection pooling

Designed using layered architecture for maintainability:

Model Layer – Employee data structure

Data Access Layer – Handles all database operations

Service Layer – Business logic and caching

UI Layer – Console-based menu navigation

Tech Stack

Language: Java 21

Database: MySQL 8.0

Libraries/Tools:

JDBC (Java Database Connectivity)

HikariCP (connection pooling)

Flyway (database migration)

Maven (dependency management & build)

I want to note that I use Optional<T> alot to avoid null errors

1. First, you might have to adjust the url, user, name, and password values in the following files:

   - config.properties
   - test_config.properties

2. In the terminal, run
   ./build.sh all
