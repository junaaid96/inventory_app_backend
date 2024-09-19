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
- **Register**: `POST - https://inventory-app-backend-1avz.onrender.com/api/users/register/`
- **Login**: `POST - https://inventory-app-backend-1avz.onrender.com/api/users/login/`
- **Logout**: `POST - https://inventory-app-backend-1avz.onrender.com/api/users/logout/`
- **Profile**: `GET, PUT, PATCH - https://inventory-app-backend-1avz.onrender.com/api/users/profile/`

### Product Management
- **List/Create**: `GET, POST - https://inventory-app-backend-1avz.onrender.com/api/products/products/`
- **Retrieve/Update/Delete**: `GET, PUT, PATCH, DELETE - https://inventory-app-backend-1avz.onrender.com/api/products/products/{id}/`

## Admin Access
- **URL**: `https://inventory-app-backend-1avz.onrender.com/admin/`
- **Default Superuser**:
  - Username: `admin`
  - Password: `12345`
