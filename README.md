# Social Media Backend with FastAPI

This repository contains the backend implementation for a social media application using FastAPI. The backend provides endpoints for user authentication, posting, commenting, and other social media functionalities.

## Features

- User Authentication (Signup, Login)
- Create, Read, Update, Delete (CRUD) operations for posts
- Like and Unlike posts
- JWT token-based authentication

## Technologies Used

- **FastAPI**: A modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.
- **SQLAlchemy**: SQL toolkit and Object-Relational Mapping (ORM) library for Python.
- **PostgreSQL**: A powerful, open source object-relational database system.
- **JWT**: JSON Web Tokens for secure user authentication.

## Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/Vishak-V/Social-Media-Backend-FastAPI.git
   cd Social-Media-Backend-FastAPI
   ```
2. **Create and Activate a Virtual Environment**
  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate
   ```
3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Set up the PostgreSQL database**
   
   Create a PostgreSQL database and update the DATABASE_URL in the config.py file with your database credentials.
5. **Start the FastAPI server**
   ```bash
   uvicorn main:app --reload
   ```

   The server will be available at http://127.0.0.1:8000



