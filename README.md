# security-with-springboot
Spring Boot server with secure user auth(jwt) using H2 Database

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



### Description:
```
Implements a REST API that includes endpoints for user login and signup functionality.
The login endpoint verifies user credentials and generate a web token upon successful authentication.
The signup endpoint allows users to create new accounts and store their information securely in the H2 database.
There is a hello endpoint which works only post the Auth and returns “Hello from Tanmay”
```

Security and Web Tokens:
```
Implements appropriate security measures to protect user data and prevent unauthorized access.
Uses web tokens (JWT - JSON Web Tokens) for user authentication and authorization.
Ensures that only authenticated users can access protected resources.
```

Database:
```
Utilizes the H2 database for storing user account information.
```
