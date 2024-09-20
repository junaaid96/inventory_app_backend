# Product Inventory App Backend

This is the backend for an inventory management application built with Django REST Framework.

## Getting Started

### Prerequisites
- [Python 3.x](https://www.python.org/)
- [Django](https://www.djangoproject.com/)
- [Django REST Framework](https://www.django-rest-framework.org/)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/junaaid96/product-inventory-backend.git
   cd product-inventory-backend
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

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

## Django Admin Access
- **URL**: `https://inventory-app-backend-1avz.onrender.com/admin/`
- **Superuser**:
  - Username: `admin`
  - Password: `12345`

## Frontend Repository

The frontend for this application is available in a separate repository. You can find it at:

[Product Inventory Frontend](https://github.com/junaaid96/inventory_app_frontend)

Please refer to the frontend repository's README for installation and usage instructions.
