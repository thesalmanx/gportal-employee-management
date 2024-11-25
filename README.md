# 🌟 GPortal: Employee & Department Management System

Welcome to GPortal – a dynamic web application for managing employees and departments effortlessly! Whether you're adding employees, assigning them to departments, or organizing your data, GPortal has got you covered. 🚀

## 🛠️ Technologies Used
- Frontend: Vue.js 🌐
- Backend: Django & Django Rest Framework (DRF) 🐍
- Database: PostgreSQL 🐘
- Package Management: Poetry 📦

## 🚀 Features
- Add new employees with ease 👤
- Organize employees by department 📂
- Intuitive and responsive user interface 🖥️
- Backend API powered by Django Rest Framework

 ## ⚡ Getting Started
 ### Prerequisites
 Make sure you have the following installed on your machine:
  - Node.js and npm (for the frontend)
  - Python and Poetry (for the backend)
  - PostgreSQL (for the database)

 ## 🏗️ Installation
 ### 1. Clone the Repository
```bash
  git clone https://github.com/thesalmanx/gportal-employee-management.git  
  cd gportal  
```

### 2. Frontend Setup
```bash
  cd frontend  
  npm install  
  npm run serve  
```

### 3. Backend Setup
```bash
  cd ../backend  
  poetry install  
```

### 4. Database Setup
- Create a PostgreSQL database.
- Update the database configurations in backend/settings.py:
  ```bash
    DATABASES = {
      'default': {
          'ENGINE': 'django.db.backends.postgresql',
          'NAME': 'your_database_name',
          'USER': 'your_username',
          'PASSWORD': 'your_password',
          'HOST': 'localhost',
          'PORT': '5432',
      }
  }

Apply Migrations
```bash
  poetry run python manage.py migrate  
```

## 🎉 Running the Project
### 1. Start the Backend Server
```bash
  poetry run python manage.py runserver  
```
### 2. Start the Frontend Development Server
```bash
cd ../frontend  
npm run serve  
```

## 🌟 How It Works
### Add Departments:
Create new departments to organize your employees.

### Add Employees:
Assign employees to their respective departments while filling in details like name, photo, and joining date.

### View and Manage Data:
Browse, update, or delete employees and departments seamlessly.

### ✨ Made with ❤️ by Muhammad Salman








