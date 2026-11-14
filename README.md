# Employee Management API

## Project Overview
The Employee Management API is a REST API developed using Python, Django, and Django REST Framework. It allows users to manage employee records through CRUD operations.

## Technologies Used
- Python
- Django
- Django REST Framework
- SQLite
- Visual Studio Code

## Employee Details
Each employee record contains:
- ID
- Name
- Email
- Department
- Salary

## API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| GET | `/api/` | Get all employees |
| POST | `/api/` | Create a new employee |
| GET | `/api/<id>/` | Get employee details |
| PUT | `/api/<id>/` | Update employee |
| PATCH | `/api/<id>/` | Partially update employee |
| DELETE | `/api/<id>/` | Delete employee |

## CRUD Operations
- Create: Add new employee records.
- Read: Retrieve employee records.
- Update: Modify employee information.
- Delete: Remove employee records.

## How to Run the Project

1. Clone the repository:
   `git clone https://github.com/neeraj317/Employee-Management-API.git`

2. Open the project folder.

3. Create a virtual environment:
   `python -m venv venv`

4. Activate the environment:
   `venv\Scripts\activate`

5. Install dependencies:
   `pip install django djangorestframework`

6. Run migrations:
   `python manage.py migrate`

7. Start the development server:
   `python manage.py runserver`

8. Open:
   `http://127.0.0.1:8000/api/`

## Project Status
CRUD operations have been tested successfully using Django REST Framework's browsable API.
