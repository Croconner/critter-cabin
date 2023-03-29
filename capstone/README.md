Animal Shelter Full Stack Application

This is a full stack web application built using Java and Spring Boot on the backend, and Vue.js on the frontend. The application is designed for an animal shelter to manage their pets and volunteers.

Installation

Clone the repository.
Install PostgreSQL on your machine.
Using bash navigate to critter-cabin/capstone/java/database and run the command 'sh create.sh'.
Update the database configuration in application.properties to match your database configuration.
Run the application by executing npm run serve in your terminal.
Open your browser and navigate to http://localhost:8080 to view the application.
Functionality
User Accounts
The application allows users to sign up and log in as volunteers. Once a user signs up, they will receive an email with their username and password. When the user logs in for the first time, they will be prompted to reset their password. The application uses Spring Security to handle user authentication and authorization.

Pet Management

Volunteers can view all the pets in the shelter, and can add new pets to be adopted or edit the information for existing pets. Volunteers can also approve or deny adoption applications for pets.

Volunteer Management

Admins can manage volunteers by accepting or rejecting applications, as well as removing current volunteers. When a volunteer application is accepted, an email is sent to the volunteer with their login credentials.

Email Notifications

When a volunteer's application is accepted or rejected, they will receive an email notifying them of the decision.

Technologies Used

Java
Spring Boot
Vue.js
PostgreSQL
Spring Security
