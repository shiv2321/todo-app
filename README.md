﻿# To-Do List Application

## Overview

This is a simple and efficient To-Do List application built using Django. It allows users to create, manage, and track their tasks with ease.

## Features

- User authentication (Signup/Login/Logout)
- Add, update, and delete tasks
- Responsive UI with Django templates

## Technologies Used

- **Backend:** Django
- **Frontend:** Django Templates, Bootstrap
- **Database:** SQLite
- **Authentication:** Django's built-in authentication system

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/shiv2321/todo-app.git
   cd Django-todo-app

   ```

2. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py migrate
   ```
5. Create a superuser:
   ```sh
   python manage.py createsuperuser
   ```
6. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage

- Open `http://127.0.0.1:8000/` in your browser.
- Register/Login to manage your tasks.
- Add new tasks, mark them as complete, or delete them.

## API Endpoints

| Method | Endpoint         | Description       |
| ------ | ---------------- | ----------------- |
| GET    | /api/tasks/      | Get all tasks     |
| POST   | /api/tasks/      | Create a new task |
| PUT    | /api/tasks/{id}/ | Update a task     |
| DELETE | /api/tasks/{id}/ | Delete a task     |

## Contributing

Feel free to contribute by forking the repository, making changes, and submitting a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any queries, feel free to reach out:

- **GitHub:** [shiv2321](https://github.com/shiv2321)
