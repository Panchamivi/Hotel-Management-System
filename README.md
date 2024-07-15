# Hotel-Management-System
This Hotel Management System project uses JDBC (Java Database Connectivity) to manage hotel reservations and customer information in a relational database. It allows users to perform various operations such as reserving rooms, viewing reservations, retrieving room numbers based on reservations, updating reservations, and deleting reservations.
# Components
Database Connection:

The project uses a MySQL database to store data related to reservations.
The connection to the database is established using JDBC.
Database Structure:

A table named reservations is used to store reservation details such as reservation ID, guest name, room number, contact number, and reservation date.
JDBC Setup:

The JDBC driver for MySQL (com.mysql.cj.jdbc.Driver) is loaded.
The database connection URL, username, and password are specified to establish a connection to the database.
