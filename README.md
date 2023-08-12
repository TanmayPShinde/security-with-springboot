# security-with-springboot
Spring Boot Backend Server with Secure User Auth (jwt) using the Java based H2 Database

## To setup and run this project, please follow these instrustions:
### Step1
clone the repository
### Step1
Follow editor procedures to install Maven Dependencies included in pom.xml
### Step1
use this command to run the server on port 8080
```
./mvnw spring-boot:run
```
### Step4
Go to this url and set confirm the User Model in the H2 Database
```
http://localhost:8080/h2-ui
```
### And you are all set

### API Endpoints:
```
1. /api/auth/signup
2. /api/auth/signin
3. /api/auth/signout
4. /api/hello
```

## Objective:

In this assignment, your task is to create a backend for a login and signup REST API with security features and web tokens for authentication. You will be using the H2 database for this assignment, and the project should be built on the Spring Boot framework.

Here are the specific requirements for the assignment:

Backend Development:
```
Implement a REST API that includes endpoints for user login and signup functionality.
The login endpoint should verify user credentials and generate a web token upon successful authentication.
The signup endpoint should allow users to create new accounts and store their information securely in the H2 database.
There should a hello endpoint which should work only post the Auth and should return “Hello from GreenStitch”
```

Security and Web Tokens:
```
Implement appropriate security measures to protect user data and prevent unauthorized access.
Use web tokens (e.g., JWT - JSON Web Tokens) for user authentication and authorization.
Ensure that only authenticated users can access protected resources.
```

Database:
```
Utilize the H2 database for storing user account information.
Design the necessary database schema to store user details securely.
```

Project Setup and Documentation:
```
Set up the project using Spring Boot.
Include a README file that provides clear instructions for installing and setting up the project.
Document any additional dependencies or libraries used in the project.
Your submission should include the source code for the working backend implementation, including all necessary configurations, controllers, services, and data access components. Additionally, provide the README file with installation and setup instructions for easy deployment and testing.
Please ensure that your code is well-structured, follows best practices, and includes appropriate error handling and validation.
```
