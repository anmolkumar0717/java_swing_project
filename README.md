# Inventory Management System

This is a simple inventory management system built using Java Swing for the user interface and JDBC for database connectivity.

## Features

- **User Interface**: The system provides a user-friendly interface built using Java Swing, allowing users to interact with the system easily.
- **Database Connectivity**: JDBC (Java Database Connectivity) is used to connect the application to a relational database, enabling data storage and retrieval.
- **CRUD Operations**: Users can perform CRUD (Create, Read, Update, Delete) operations on inventory items, including adding new items, viewing existing items, updating item details, and deleting items.
- **Search Functionality**: The system includes a search feature allowing users to search for specific items based on various criteria such as name, category, or ID.
- **Validation**: Input validation is implemented to ensure that only valid data is entered into the system.
- **Data Persistence**: The inventory data is stored in a database, ensuring data persistence and scalability.

## Technologies Used

- **Java**: Core programming language used for application logic.
- **Java Swing**: GUI toolkit used to create the user interface.
- **JDBC (Java Database Connectivity)**: API for connecting Java applications to databases.
- **MySQL**: Relational database used for storing inventory data.

## Project Structure

- `src/`: Contains the Java source code files.
  - `Main.java`: Main class to start the application.
  - `InventoryItem.java`: Class representing an inventory item.
  - `InventoryDAO.java`: Data Access Object (DAO) class for interacting with the database.
  - `InventoryUI.java`: User Interface class for the inventory management system.
- `sql/`: Contains SQL scripts for creating the database and tables.
  - `create_database.sql`: Script to create the database.
  - `create_table.sql`: Script to create the inventory table.
- `lib/`: Contains JDBC driver JAR file.
- `README.md`: Documentation file.

## Getting Started

1. **Clone the Repository**:

   ```bash
   git clone <github.com/anmolkumar0717/java_swing_project/tree/main/log_in>
