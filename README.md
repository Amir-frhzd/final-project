This is a full-stack web application built as the final project for the Maktabkhooneh Django Bootcamp.  
It simulates an online learning platform with user authentication, blog, and dynamic content handling using Django.

---

## 🚀 Features

### 🔐 Authentication System
- Secure sign-up with validation (first name, last name, email, password)
- Email uniqueness check – no duplicate accounts
- Login & Logout
- Forgot Password: recover password via email (username or email supported)
- Password reset flow using Django's built-in mechanisms

### 🧑‍🎓 Pages & Functionality
- Home Page – Responsive landing with navigation
- Courses Page – Lists available courses (static for now)
- Blog/News Page:
  - Recent posts
  - Category & tag-based filtering
  - Post view counter
  - Search functionality
  - Some posts only visible to logged-in users
- About Us Page
- Contact Us Page – Contact form with validation

### 🧠 Backend Focus
- Modular Django app structure
- Separated apps for:
  - Blog
  - Authentication
  - User management
  - Courses
- Custom models and views
- Use of Django's ORM, class-based views, and URL routing

---

## 🛠 Technologies Used

- Python 3 / Django
- SQLite (for development)
- HTML5 / CSS3 / Bootstrap (purchased template)
- Git & GitHub for version control

---

## 📷 Screenshots

_Coming soon..._

---

## 📂 Installation (For Local Setup)

`bash
git clone https://github.com/Amir-frhzd/final-project.git
cd final-project
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
