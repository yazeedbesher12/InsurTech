Project Name

InsurTech

Overview

The Vehicle Insurance Management System is a desktop application built with Java, JavaFX, and Maven. It allows users to manage:

Clients information

Vehicles data

Vehicle insurance records

The project demonstrates database operations (CRUD), GUI design, and clean project structure following common Java best practices.

Features

Client management (add, update, view)

Vehicle management

Vehicle insurance management

Database integration

JavaFX-based user interface

MVC-style project structure

Technologies Used

Java

JavaFX

Maven

JDBC / Database

FXML

CSS (for UI styling)

Project Structure
src/
 └── main/
     ├── java/
     │   └── com.example.demo6
     │       ├── ClientCont.java
     │       ├── VehicleCont.java
     │       └── VehicleInsuranceController.java
     └── resources/
         ├── *.fxml
         ├── *.css
         └── images/
How to Run the Project

Make sure Java JDK is installed.

Make sure Maven is installed.

Open the project in an IDE such as IntelliJ IDEA or Eclipse.

Configure the database connection if required.

Run the main application class.

Database

The application uses a relational database to store clients, vehicles, and insurance data.

Database connection is handled using JDBC.

Purpose

This project was developed as an educational / university project to practice:

Java desktop development

Database integration

MVC architecture

GUI design using JavaFX

Future Improvements

User authentication

Advanced search and filtering

Better error handling

Improved UI/UX
