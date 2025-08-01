# Student Performance API

This project provides a RESTful API for accessing and managing student performance data using **Node.js**, **Express**, **MySQL**, and **Swagger** for documentation.

## Features

- Retrieve all student records
- Get a specific student by ID
- Add a new student
- Update an existing student
- Delete a student
- Automatically calculate and update performance grades via triggers
- Stored procedures for performance metrics
- Swagger UI for interactive documentation

## Technologies Used

- Node.js & Express
- MySQL (phpMyAdmin)
- Swagger (OpenAPI)
- dotenv
- Nodemon

## Prerequisites

- Node.js and npm
- MySQL Server (configured on port **3307**)
- phpMyAdmin
- Git

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/student-performance-api.git
cd student-performance-api
2. Install dependencies
npm install
3. Set up environment variables
Create a .env file:

env
Copy
Edit
DB_HOST=localhost
DB_USER=root
DB_PASS=
DB_NAME=student_perfomance
DB_PORT=3307
PORT=3000
4. Start the server
bash
Copy
Edit
nodemon index.js
Server will run on:
http://localhost:3000

5. Access Swagger Docs
Visit:
http://localhost:3000/api-docs

API Endpoints
Method	Route	Description
GET	/api/students	Get all students
GET	/api/students/:id	Get student by ID
POST	/api/students	Add new student
PUT	/api/students/:id	Update student
DELETE	/api/students/:id	Delete student






