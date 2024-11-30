# Blog Post Website

A web application built using Django that allows users to create and manage blogs. Users can register, log in, update their profile, and post blogs with options to edit and delete them.

## Features

- **User Registration**: Users can sign up for an account.
- **User Login**: Registered users can log in to their account.
- **User Logout**: Users can log out securely.
- **Profile Update**: Users can update their profile information.
- **Post a Blog**: Authenticated users can create and publish blog posts.
- **Update a Post**: Users can edit their existing blog posts.
- **Delete a Post**: Users can delete their own blog posts.

## Installation

Follow these steps to run the project on your local machine.

### Prerequisites

- Python (3.10 or later)
- Django (3.1 or later)
- Virtual environment (optional but recommended)
- SQLite (default database for Django)

### Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   venv\Scripts\activate

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

4. **Run Migrations**:
   ```bash
   python manage.py makemigrations
   python manage.py migrate

5. **Start the Development Server**:
   ```bash
   python manage.py runserver

6. Open your browser and go to http://127.0.0.1:8000/ to access the application.

## Technologies Used
- Backend: Django
- Frontend: HTML, CSS, Bootstrap (or any framework used)
- Database: SQLite
