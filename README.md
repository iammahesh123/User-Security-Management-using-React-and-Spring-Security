# User Security Management using React and Spring Security

This project demonstrates user security management using React for the frontend and Spring Security for the backend. It includes functionality for user signup, signin, and a simple dashboard.

## Overview

User security management is a crucial aspect of any web application. This project showcases how to implement secure authentication and authorization mechanisms using React and Spring Security.

## Features

- `User signup`: Allows new users to create an account.
- `User signin`: Allows registered users to sign in to their accounts.
- `Authentication`: Secure authentication using JSON Web Tokens (JWT).
- `Authorization`: Role-based access control (RBAC) to restrict access to certain resources.
- `Simple Dashboard`: A basic dashboard interface for authenticated users.

## Project Structure

- `frontend`: Contains the React frontend application.
- `backend`: Contains the Spring Boot backend application.

## Frontend (React)

### Setup

1. Navigate to the frontend directory:

```bash
cd frontend-react
```
2. Install dependencies:
```bash
npm install
```
3. Start the frontend server:
```bash
npm start
```
4. Access the frontend application in your web browser: http://localhost:3000
## Backend (Spring Security)
### Setup
1. Navigate to the backend directory:
```bash
cd backend-spring
```
2. Start the backend server:
```bash
mvn spring-boot:run
```
3. The backend server will run on http://localhost:8080
## Usage
- Sign up for a new account using the signup page.
- Sign in to your account using the signin page.
- Upon successful signin, you will be redirected to the dashboard.

## Configuration
- **Frontend:** Configuration settings such as API endpoints are defined in the .env file in the frontend directory.
- **Backend:** Configuration settings for Spring Security are defined in the application.properties file in the backend directory.
## Dependencies
- Frontend (React)
- React
- React Router
- Axios
- Backend (Spring Security)
- Spring Boot
- Spring Security
- Spring Data JPA

## Contributing
Contributions are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License.
