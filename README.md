# Skola E-Learning Platform

Skola E-Learning Platform is a specialized platform designed to provide courses to students. Built using the Python Django framework, it offers a streamlined environment for managing and accessing educational content online.

## Features

- **Course Catalog**: Browse and enroll in available courses.
- **User Authentication**: Secure login and registration system for students.
- **Course Enrollment**: Easily enroll in desired courses.
- **Content Access**: Access course lectures, assignments, and supplementary materials.
- **Responsive Design**: Optimized for desktop and mobile devices for seamless learning.

## Installation

### Clone the Repository

```bash
git clone https://github.com/Priyanshu2sh/Skola-E-Learning-Platform.git
cd skola-e-learning-platform
```

### Create a Virtual Environment

```bash
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create a Superuser

```bash
python manage.py createsuperuser
```

### Start the Development Server

```bash
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to access the Skola E-Learning Platform.

## Usage

- **Course Enrollment**: Browse the course catalog and enroll in desired courses.
- **Access Course Materials**: View lectures, complete assignments, and access supplementary resources.
- **User Profile**: Manage personal information and track enrolled courses.