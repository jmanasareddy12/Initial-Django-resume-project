💼 Django Resume Website

A personal resume and portfolio website built using Django, designed to showcase skills, projects, and personal information through a clean multi-page web interface.

This project demonstrates the fundamentals of Django web development including routing, templates, static files, and project structure.

🚀 Features

🏠 Home page with introduction

👤 About section

📂 Projects page

📞 Contact page

🎨 Static CSS styling

🔗 Django URL routing

🧩 Modular app structure

🧠 Technologies Used

Python

Django

HTML5

CSS3

SQLite (default Django database)

Git & GitHub

📁 Project Structure
myresume/
│
├── manage.py
├── myresume/          # Project settings & configuration
│
├── resume/            # Main Django app
│   ├── views.py
│   ├── urls.py
│   ├── models.py
│
├── templates/         # HTML templates
│
├── static/            # CSS / static files
│
└── README.md

⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/yourusername/Initial-Django-resume-project.git
cd Initial-Django-resume-project

2️⃣ Create virtual environment
python -m venv myenv
source myenv/bin/activate     # Linux / Mac

3️⃣ Install dependencies
pip install -r requirements.txt


If requirements.txt is missing:

pip install django

4️⃣ Run migrations
python manage.py migrate

5️⃣ Start development server
python manage.py runserver


Open in browser:

http://127.0.0.1:8000

🧪 Project Status

🚧 Work in Progress

Currently improving:

Better UI design

Bootstrap integration

Responsive layout

Additional portfolio features

📌 Learning Goals

This project was created to practice:

Django project setup

App creation and configuration

Template rendering

Static file handling

URL mapping and views

Version control with GitHub

👩‍💻 Author

J Manasa Reddy
