Electricity Billing System Project 
The Electricity Billing System Project is a Java desktop application developed using Java Swing, aimed at managing electricity billing efficiently. This application provides a user-friendly interface for handling various aspects of electricity billing, including customer management, meter readings, bill calculations, and statement generation.

Application Features
Admin Functions:

Create New Customers: Admins can add new customers and assign meter information.
View Customer Details: Admins can access and review details for all customers.
Bill Calculation: Admins have the capability to calculate and manage bills for all customers.
User Functions:

Account Creation: Users can create their own accounts after the admin sets up their meter information.
Bill Calculation and Payment: Users can calculate and pay their electricity bills through the application.
Personal Information Update: Users can update their personal details as needed.
Generate Bills: Users can generate and view their electricity bills.
Meter Information & Payment Status: Users can check their meter information and the status of their bill payments.
Project Details
Development Environment: The project is developed using IntelliJ IDEA.

JDBC Integration: A JDBC library is included to facilitate the connection between the Java application and the MySQL database.

Class Structure: The application is structured into various classes to ensure a seamless user experience:

Splash Screen: Displays an introductory screen.
Signup Screen: Manages user account creation.
Login Screen: Handles user login.
Main Class: Serves as the central class for application logic.
New Customer: Manages new customer entries.
Pay Bill: Handles bill payment processes.
Generate Bill: Generates bills for customers.
Customer Details: Manages and displays customer information.
Calculate Bill: Performs bill calculations.
Bill Details: Displays detailed bill information.
Deposit Details: Manages deposit-related information.
Meter Info: Manages meter-related details.
Update Information: Allows users to update their personal information.
View Information: Facilitates viewing of information.
Database Class (JDBC - MySQL): Manages database connections and interactions.
Database Structure
The MySQL database used in this project contains the following tables:

Signup Table: Stores user credentials (UserName, Password).
New Customer Table: Contains customer details (Name, MeterNumber, Address, State, City, Email, Phone).
