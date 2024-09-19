# Product Inventory App Backend

This is the backend for an inventory management application built with Django REST Framework.

## Getting Started

### Prerequisites
- Python 3.x
- Django

### Installation
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`

### Running the Server
```
python manage.py runserver
```

## API Endpoints

### User Management
- **Register**: `POST /users/register/`
- **Login**: `POST /users/login/`
- **Logout**: `POST /users/logout/`
- **Profile**: `GET, PUT, PATCH /users/profile/`

### Product Management
- **List/Create**: `GET, POST /products/products/`
- **Retrieve/Update/Delete**: `GET, PUT, PATCH, DELETE /products/products/{id}/`

## Admin Access
- **URL**: `/admin/`
- **Default Superuser**:
  - Username: `admin`
  - Password: `12345`
