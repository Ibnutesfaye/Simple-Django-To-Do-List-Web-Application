# 🎯 Django To-Do List Web Application

A professional, full-featured To-Do List application built with the Django framework. This project features a modern **Glassmorphism UI** with a custom CSS landscape background, full CRUD functionality, and user authentication.

---

## ✨ Features

### 🛠 Core Functionality (CRUD)

- **Add Tasks**: Create new daily tasks with titles andescriptions.
- **View Tasks**: A clean, responsive list view of all your tasks.
- **Edit Tasks**: Update existing task details at any time.
- **Delete Tasks**: Remove tasks you no longer need.
- **Mark as Completed**: Toggle task status between 'Pending' and 'Completed' with visual strikethrough styling.

### 🔐 Security & Personalization

- **User Authentication**: Secure Login and Registration system.
- **Data Privacy**: Users can only see and manage their own tasks.
- **Django Admin**: Built-in admin panel for site-wide data management.

### 🎨 Premium UI/UX

- **Glassmorphism**: Elegant frosted-glass cards with backdrop blur.
- **Minimalist Design**: Underlined inputs with custom SVG icons.
- **Landscape Background**: Pure CSS/SVG landscape with mountains, trees, and birds.
- **Search & Filtering**: Real-time keyword search and status-based filtering (All/Pending/Completed).

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed
- Django installed (`pip install django`)

### Installation & Setup

1. **Navigate to the project directory**:

   ```powershell
   cd "c:\Django To-Do List Web Application"
   ```

2. **Apply Database Migrations**:

   ```powershell
   python manage.py migrate
   ```

3. **Start the Development Server**:

   ```powershell
   python manage.py runserver
   ```

4. **Access the Application**:
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your web browser.

---

## 🔐 Admin Access

I have pre-configured a superuser for testing purposes:

- **Admin URL**: [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)
- **Username**: `admin`
- **Password**: `admin123`

---

## 📂 Project Structure

- `todoproject/` - Project settings and main URL configuration.
- `tasks/` - Main application app (Models, Views, Forms, URLs).
- `templates/` - HTML files including the base layout and auth templates.
- `static/` - Custom CSS and premium UI assets.
- `manage.py` - Django's command-line utility.

---

## 🛠 Tech Stack

- **Backend**: Django (Python)
- **Database**: SQLite (built-in)
- **Frontend**: HTML5, Vanilla CSS3 (Custom styling)
- **Design Pattern**: MVT (Model-View-Template)

---

## 📈 Learning Objectives Demonstrated

- Django project/app scaffolding.
- MVT Architecture implementation.
- Handling full CRUD operations in SQLite.
- Custom User Authentication and scoping.
- Advanced CSS techniques (Glassmorphism, SVG backgrounds).
