
# User Management Project

This project is a comprehensive user management system built using Python, Django, React, Redux, JWT authentication, Tailwind CSS, and Django Rest Framework (DRF). It includes separate user and admin interfaces, providing robust functionality for managing users and their permissions.

## Features

- **User Interface**: The project offers a user-friendly interface for both regular users and administrators.
- **Authentication**: Users are authenticated using JSON Web Tokens (JWT), ensuring secure access to the system.
- **User Management**: Regular users can register, login, update their profiles, and perform various user-specific actions.
- **Admin Dashboard**: Administrators have access to an admin dashboard where they can manage users, view user details, and assign permissions.
- **RESTful API**: The backend is built with Django Rest Framework (DRF), providing a RESTful API for seamless communication between the frontend and backend.

## Technologies Used

- **Python**: Programming language used for backend development.
- **Django**: High-level Python web framework for rapid development and clean design.
- **React**: JavaScript library for building interactive user interfaces.
- **Redux**: State management library for managing application state in React.
- **JWT**: JSON Web Tokens for secure authentication and authorization.
- **Tailwind CSS**: Utility-first CSS framework for styling the user interface.
- **Django Rest Framework (DRF)**: Django extension for building APIs.

## Setup Instructions

1. Clone the repository: `git clone https://github.com/fauzudheen/User-Management.git`
2. Navigate to the project directory: `cd user-management-project`
3. Install dependencies for the backend:
   ```
   cd backend
   pip install -r requirements.txt
   ```
4. Run migrations: `python manage.py migrate`
5. Start the Django development server: `python manage.py runserver`
6. Install dependencies for the frontend:
   ```
   cd ../frontend
   npm install
   ```
7. Start the React development server: `npm start`

## Usage

- Access the user interface at `http://localhost:3000` for regular users.
- Access the admin dashboard at `http://localhost:3000/admin` for administrators.
- Use the provided authentication endpoints to register, login, and manage users.

