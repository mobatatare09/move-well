# MoveWell

## Introduction

**MoveWell** is a fitness tracking web application built using Django, aimed at helping users log and track their fitness progress. Users can register, log in, post their fitness results (such as weight and height), and view their calculated BMI (Body Mass Index). This project follows Agile principles, focusing on user experience and CRUD functionality, with features for authentication, authorization, and cloud deployment.

---

## Wireframe

The **MoveWell** wireframe includes the following pages:
- **Home Page:** Includes options to register or log in.
- **Registration Page:** Form for users to sign up with a username, email, and password.
- **Login Page:** Form for users to log in with existing credentials.
- **Profile Page:** Displays logged fitness results and a form to post new results.
- **Edit/Delete Page:** Allows users to modify or delete their fitness records.

---

## ERD Scheme

The **Entity-Relationship Diagram (ERD)** for MoveWell consists of:
- **User Entity:** Handles user information (username, email, password).
- **FitnessResult Entity:** Stores fitness entries (weight, height, BMI) linked to the user.
- **Relationships:** A one-to-many relationship between `User` and `FitnessResult` (one user can have many fitness results).

---

## Features

### MVP Features:
- **User Registration & Login:** Secure user authentication and authorization.
- **Post Fitness Results:** Users can log their weight and height to calculate BMI.
- **View Fitness Results:** Users can view their past results with the corresponding BMI.
- **Edit/Delete Results:** Users can update or delete their previous fitness entries.

### Additional Features (Post-MVP):
- **Progress Tracking:** Graphical display of fitness progress over time.
- **Goal Setting:** Users can set and track fitness goals.

---

## Technologies Used
- **Django** for backend
- **HTML/CSS/JavaScript** for frontend
- **PostgreSQL** for database (optional for cloud deployment)
- **Bootstrap** for UI design
