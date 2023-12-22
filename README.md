# Hospital Management System
sturture of project:
# Package com.example.hospital_management_system
# Class HelloApplication:
The entry point for the JavaFX application.
Responsible for creating and displaying the main application window.
Loads the initial FXML (register-view.fxml).
# Class AddPatientController:
Controller for adding a new patient.
Displays the patient addition form and handles user actions.
# Class Patient:
Entity class representing a patient.
Used to store information about a patient.
# Class PatientAccountController:
Controller for patient accounting.
Displays information about patients and handles user actions.
# Class RegisterController:
Controller for registering new users.
Handles user registration actions.
# Class LoginController:
Controller for user login.
Handles user login actions.
Package com.example.hospital_management_system.database
# Class DbFunctions:
Contains methods for interacting with the database (e.g., connecting to the database, executing SQL queries, creating tables).
Implements functions for working with users and patients.
Package com.example.hospital_management_system.entities
# Class User:
Entity class representing a system user.
Used to store information about users.
Resources
# FXML Files:
register-view.fxml: Registration form.
patient-accounting-view.fxml: Patient accounting form.
login-view.fxml: Login form.
add-patient-view.fxml: Patient addition form.
# Other Resources:
Images, styles, and other resources used in the application.

## Overview

This project is a Hospital Management System designed to manage patient records, appointments, and related information. It utilizes Java for the backend logic, JavaFX for the user interface, and PostgreSQL as the database.

## Features

- Patient Management: Add, update, and view patient records.
- User Interface: JavaFX-based graphical user interface for easy navigation.
- Database Integration: Utilizes PostgreSQL for data storage.

## Installation

1. Clone the repository: `https://github.com/galanien/Hospital-management-system.git`
2. Open the project in your preferred Java IDE.

## Usage

1. Build and run the project.
2. Use the graphical interface to interact with patient records.

## Database Setup

1. Install PostgreSQL on your local machine.
2. Create a database named `hospital_management_system`.
3. Update the database connection details in the code.

## Dependencies

- Java 8 or later
- JavaFX
- PostgreSQL JDBC Driver


