# Job Portal Website Backend

A backend system for a job portal website developed using FastAPI and Python.

## Overview

This project was created as a beginner-friendly demonstration of how a backend system for a job portal website can be developed using FastAPI.

The backend handles job postings, user management, database operations, and API-based communication for a job portal platform. It serves as an introduction to backend development, REST API creation, database integration, and modern Python web frameworks.

## Features

* REST API development using FastAPI
* Job posting management
* User data handling
* Database connectivity and operations
* API request and response handling
* Beginner-friendly backend project structure
* Easy to customize and expand

## Technologies Used

* Python
* FastAPI
* SQLAlchemy
* SQLite
* Pydantic

## Project Structure

```text
Job-Portal-Website-Backend/
│
├── main.py          # Main FastAPI application and API route handling
├── database.py      # Database configuration and connection setup
├── models.py        # Database table models and schema definitions
├── schemas.py       # Pydantic schemas for request and response validation
└── README.md        # Project documentation and setup instructions
```

## How to Run the Project

1. Clone the repository.
2. Open the project folder.
3. Install the required dependencies:
```bash
pip install fastapi uvicorn sqlalchemy pydantic
```
4. Run the FastAPI server:
```bash
uvicorn main:app --reload
```
5. Open the API in your browser:
```text
http://127.0.0.1:8000
```
6. Access the automatic API documentation:
```text
http://127.0.0.1:8000/docs
```

## Learning Purpose

This repository was created for learning purposes to understand:

* Backend development using FastAPI
* REST API creation
* Database integration with SQLAlchemy
* Request and response validation using Pydantic
* Basic web backend architecture

## Author

Akibul Hasan Anik

## License

This project is open-source and available for educational purposes.
