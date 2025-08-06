# django_drf_api_notes


# 📝 Notes REST API

A simple and powerful RESTful API to manage notes. Built with Django REST Framework.

## 🚀 Features

- CRUD operations for notes (Create, Read, Update, Delete)
- Token-based authentication (optional)
- Timestamping for created and updated notes
- Pagination and filtering support
- JSON responses

---

## 🛠️ Tech Stack

- Python 3.10+
- Django
- Django REST Framework
- SQLite (or PostgreSQL/MySQL supported)

---

## 📦 Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/notes-api.git
cd notes-api

# 2. Create virtual environment and activate
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Create superuser (optional)
python manage.py createsuperuser

# 6. Run the development server
python manage.py runserver
