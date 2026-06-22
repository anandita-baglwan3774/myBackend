# myBackend – Role-Based Authentication & User Management API

A secure backend API built using Node.js, Express.js, TypeScript, and PostgreSQL. The project provides authentication, authorization, user management, and role-based access control using JWT.

## Features

* User Registration & Login
* JWT Authentication
* Role-Based Access Control (RBAC)
* Password Hashing with bcrypt
* PostgreSQL Database Integration
* RESTful API Architecture
* Swagger API Documentation
* Modular Project Structure
* Middleware-Based Security

## Tech Stack

* Node.js
* Express.js
* TypeScript
* PostgreSQL
* JWT (JSON Web Tokens)
* bcrypt
* Swagger
* Bun Runtime

## Project Structure

```bash
src/
├── config/
├── middleware/
├── modules/
│   ├── auth/
│   └── users/
├── utils/
└── server.ts
```

## API Modules

### Authentication

* Register User
* Login User
* Generate JWT Token

### User Management

* Create User
* Get All Users
* Get User By ID
* Delete User

## Security Features

* Password Hashing using bcrypt
* JWT-Based Authentication
* Protected Routes
* Role-Based Authorization Middleware

## Installation

```bash
git clone <repository-url>
cd myBackend
npm install
```

## Environment Variables

Create a `.env` file:

```env
PORT=3000
DATABASE_URL=your_database_url
JWT_SECRET=your_secret_key
```

## Run Project

```bash
npm run dev
```

Server:

```bash
http://localhost:3000
```

## Future Improvements

* Refresh Tokens
* Email Verification
* Password Reset
* Audit Logs
* Docker Deployment

## Author

Anandita Baglwan
