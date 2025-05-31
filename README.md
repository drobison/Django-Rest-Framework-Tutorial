# Django REST Framework - Tutorial
Learn how to build REST APIs with Django &amp; the Django Rest Framework.

## Features
- RESTful API endpoints
- Django REST Framework integration
- JSON serialization
- Authentication and permissions
- API documentation

## Prerequisites
- Python 3.8+
- pip (Python package manager)

## Setup Instructions

### 1. Clone the Repository
```bash
git clone <repository-url>
cd Django-Rest-Framework-Tutorial
```

### 2. Create Virtual Environment
```bash
python -m venv venv
```

### 3. Activate Virtual Environment
**On Windows:**
```bash
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
source venv/bin/activate
```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Database Setup
```bash
python manage.py makemigrations
python manage.py migrate
```

### 6. Create Superuser (Optional)
```bash
python manage.py createsuperuser
```

### 7. Start Development Server
```bash
python manage.py runserver
```

The server will start at `http://127.0.0.1:8000/`

## API Routes

### Base URL
```
http://127.0.0.1:8000/api/
```

### Available Endpoints
- `GET /api/` - API root
- `GET /api/users/` - List all users
- `POST /api/users/` - Create new user
- `GET /api/users/{id}/` - Get specific user
- `PUT /api/users/{id}/` - Update user
- `DELETE /api/users/{id}/` - Delete user

### Authentication
- Token-based authentication
- Session authentication for browsable API

## Development

### Running Tests
```bash
python manage.py test
```

### Code Style
```bash
pip install flake8
flake8 .
```

### API Documentation
Visit `http://127.0.0.1:8000/api/` in your browser for the browsable API interface.

## Project Structure
```
Django-Rest-Framework-Tutorial/
├── manage.py
├── requirements.txt
├── README.md
├── tutorial/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── quickstart/
    ├── __init__.py
    ├── admin.py
    ├── apps.py
    ├── models.py
    ├── serializers.py
    ├── views.py
    └── urls.py
```

## Contributing
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License
This project is for educational purposes.
