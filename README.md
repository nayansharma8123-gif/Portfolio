# 🌐 Django Portfolio Website

A clean, responsive and modern portfolio website built using **Django, Python, HTML, CSS and JavaScript**.

The project demonstrates how a Django application can be structured with reusable templates, static files, multiple pages, responsive layouts and a contact form.

---

## 🚀 Features

- 🏠 Modern Home page
- 👤 About page
- 📩 Contact page with form
- 🧭 Reusable navigation bar
- 🦶 Reusable footer
- 🖼️ Custom hero section and project images
- 📱 Responsive design for desktop, tablet and mobile
- 🎨 Clean and modern UI
- 📂 Django static files for CSS and images
- 🧩 Django template inheritance
- 🔗 Django URL routing
- ⚡ Smooth scrolling and hover effects
- 📦 Organized project structure

---

## 🛠️ Technologies Used

### Backend
- Python
- Django

### Frontend
- HTML5
- CSS3
- JavaScript

### Development Tools
- Git
- GitHub
- Visual Studio Code

---

## 📁 Project Structure

```text
myProject/
│
├── manage.py
│
├── myProject/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── app/
│   ├── migrations/
│   ├── templates/
│   │   ├── base.html
│   │   ├── home.html
│   │   ├── about.html
│   │   └── contact.html
│   │
│   │   └── includes/
│   │       ├── navbar.html
│   │       └── footer.html
│   │
│   ├── views.py
│   ├── urls.py
│   ├── models.py
│   └── admin.py
│
├── static/
│   ├── css/
│   │   └── style.css
│   │
│   └── images/
│       ├── logo.png
│       ├── hero.jpg
│       └── project images
│
├── requirements.txt
│
└── README.md
