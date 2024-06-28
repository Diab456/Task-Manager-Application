# Task-Manager-Application
comprehensive full-stack web application designed for managing tasks efficiently. It leverages modern web technologies to provide a robust, user-friendly platform for task management.

# Features

1- Front-end: Developed using Angular for a responsive and dynamic user interface.

2- Back-end: Built with Spring Boot to handle business logic and API services.

3- Database: PostgreSQL is used for storing task data.

4- RESTful APIs: Ensures smooth communication between the front-end and back-end.

5- Error Handling: Provides appropriate alerts and messages for various user interactions.

6- Enhanced User Experience: Improved UI with a background image and better styling.

7- Routing: Implemented navigation between different views (task list, create task).

# Tech Stack
- Java
- Spring Boot
- Angular
- PostgreSQL
- RESTful APIs
- Git/GitHub
- Maven

# Structure
## Back-end (Spring Boot) ##
- Main Application: TaskmanagerApplication.java
- Configuration: WebConfig.java
- Controllers: TaskController.java
- Models: Task.java
- Repositories: TaskRepository.java
- Services: TaskService.java
- Configuration: application.properties

##Front-end (Angular)##
- Models: task.ts
- TaskFormComponent: Handles task creation.
- TaskListComponent: Displays list of tasks.
- Services: TaskService.ts
- Routing: AppRoutingModule.ts
- Main App Module: AppModule.ts
- Global Styles: styles.css
- App Component: AppComponent.ts, AppComponent.html, AppComponent.css

# Setup and Installation
- Prerequisites
- Java JDK
- Node.js and npm
- PostgreSQL
- Maven
- Git

# Back-end Setup
##Clone the repository:##
git clone https://github.com/yourusername/taskmanager.git
cd taskmanager

# Configure PostgreSQL:
- Ensure PostgreSQL is running.
- Create a database named taskmanager.
- Update application.properties with your PostgreSQL credentials.
- Build and run the Spring Boot application:
    - mvn clean install
    - mvn spring-boot:run

# Front-end Setup
##Navigate to the front-end directory (if separated):##
- cd frontend

##Install dependencies:##
- npm install

# Run the Angular application: 
  - ng serve
  - Open your browser and navigate to http://localhost:4200.

# Usage:
 - Navigate to the Task List view to see all tasks.
 - Use the Create Task view to add new tasks.
 - Tasks can be deleted from the Task List view.





 













