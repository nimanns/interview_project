# Interview ToDo 

## Overview

This project is a to-do list application with a Django backend and a React frontend. The Django backend provides a RESTful API for managing to-do items, while the React frontend allows users to interact with this API through a user-friendly interface.

## Prerequisites

- Python 3.8 or higher
- Node.js 14.x or higher
- npm (Node Package Manager) or yarn

## Backend Setup (Django)

### 1. Clone the Repository

```bash
git clone <your-repo-url>
cd <your-repo-directory>
```

### 2. Set Up a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

- **On Windows:**

  ```bash
  venv\Scripts\activate
  ```

- **On macOS/Linux:**

  ```bash
  source venv/bin/activate
  ```

### 4. Install Django and Other Dependencies

```bash
pip install -r requirements.txt
```

### 5. Apply Migrations

```bash
python manage.py migrate
```

### 6. Run the Django Development Server

```bash
python manage.py runserver
```

The backend will be running at `http://127.0.0.1:8000/`.

## Frontend Setup (React)

### 1. Navigate to the Frontend Directory

```bash
cd frontend
```

### 2. Install Node.js Dependencies

```bash
npm install
```

or

```bash
yarn install
```

### 3. Run the React Development Server

```bash
npm start
```

or

```bash
yarn start
```

The frontend will be running at `http://localhost:3000/`.

## API Endpoints

### **Todos**

- **GET /api/todos/**: Retrieve the list of todos.
- **POST /api/todos/**: Create a new todo.
- **PATCH /api/todos/{id}/**: Update an existing todo.
- **DELETE /api/todos/{id}/**: Delete a todo.
