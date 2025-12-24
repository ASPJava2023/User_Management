User Management Mini Project (Spring Boot)
📖 Project Overview

This project is a User Management System designed to demonstrate end-to-end user onboarding, authentication, and role-based access concepts using modern Java web technologies. The application covers the complete lifecycle of a user—from registration to login, password reset, and dashboard access—following real-world enterprise requirements.

The system includes dynamic, database-driven registration forms, secure authentication, first-time login password reset enforcement, and a dashboard integrated with a third-party API to enhance user experience. The project is structured as a mini real-world use case commonly implemented in enterprise applications. 

✨ Key Features

User Registration

Country, State, and City dropdowns populated from the database

Dependent dropdown behavior (Country → State → City)

System-generated random password

Password sent to the user via email

User Login

First-time login redirects to password reset

Subsequent logins navigate directly to the dashboard

Password Reset

Old password verification

New and confirm password validation

One-time mandatory reset enforcement

Dashboard

Displays random motivational quotes

Integrated with a third-party Quotes API .

Option to fetch new quotes dynamically

🛠️ Tech Stack (Indicative)
Java
Spring Boot
Spring Security
REST APIs
Database-driven dropdowns
Third-party API integration
