# little-lemon-coursera-Project
A Django backend project for a restaurant website that displays menu items, prices, and detailed item pages using Django views, templates, models, and SQLite database.
Little Lemon is a Django-based web application developed as part of a backend development course.
The project demonstrates core Django concepts such as URL routing, views, templates, models, and database interactions.# Little Lemon – Django Backend Project

## 📌 Project Overview
Little Lemon is a Django-based backend web application developed as part of a backend development course.  
The project demonstrates core Django concepts including models, views, templates, URL routing, database interactions, and the Django admin panel.

The application allows users to browse a restaurant menu, view menu items sorted alphabetically, and navigate to detailed pages for each menu item.

---

## 🎯 Features
- Homepage with navigation
- Menu page displaying all menu items in alphabetical order
- Menu item detail page showing:
  - Item name
  - Description
  - Price
  - Associated image
- Dynamic content rendering using Django Template Language (DTL)
- Template inheritance and reusable components
- Shared footer across all pages
- Django Admin panel for managing menu items
- SQLite database for development and prototyping

---

## 🛠️ Technologies Used
- Python
- Django
- SQLite
- HTML
- Django Template Language (DTL)
- Git & GitHub

---

## 📂 Project Structure


littlelemon/
│
├── littlelemon/ # Project settings
├── restaurant/ # Main app
│ ├── models.py # Database models
│ ├── views.py # Function-based views
│ ├── urls.py # App URL configurations
│ ├── templates/ # HTML templates
│ └── static/ # Static files (images, CSS)
│
├── manage.py
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/USERNAME/littlelemon.git
cd littlelemon

2️⃣ Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3️⃣ Install dependencies
pip install django

4️⃣ Run migrations
python manage.py migrate

5️⃣ Create a superuser (optional)
python manage.py createsuperuser

6️⃣ Run the development server
python manage.py runserver


Open your browser at:

http://127.0.0.1:8000/

🔐 Admin Panel

Access the Django admin panel at:

http://127.0.0.1:8000/admin/


Use the superuser credentials to manage menu items.

📘 Learning Outcomes

Understanding Django MVT architecture

Working with function-based views

Using Django ORM for database operations

Implementing template inheritance and includes

Handling static files

Using Git for version control

📌 Notes

This project uses SQLite, which is suitable for small projects and rapid prototyping.

The project is intended for learning and demonstration purposes.

👤 Author

Basem H. A. Daqarem
