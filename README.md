# Martyna's Blog
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Jinja](https://img.shields.io/badge/jinja-white.svg?style=for-the-badge&logo=jinja&logoColor=black)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)


This is a Python-based blog project built using the Flask web framework and Bootstrap. The application uses a PostgreSQL database, which was created with the help of SQLAlchemy. Passwords are hashed and salted using sha256 to protect sensitive data.

## Features
The project includes an admin account, which has access to additional functionalities such as adding new posts, editing existing posts, deleting posts, and comments. These functionalities are disabled and hidden from regular users. The routes for these functions are forbidden for non-admin clients to prevent unauthorized access.

Registered and logged-in users can leave comments on the blog posts. The 'Contact' tab allows viewers to send an email form to the site owner's inbox using the smtplib module and SMTP protocol.

The project prioritizes cybersecurity by using an algorithm to sanitize each client's HTML input. The algorithm removes unwanted tags, attributes, unescaped characters, and unclosed or misnested tags.

## Deployment
The project is currently deployed on Render at https://martyna-blog.onrender.com.

## Preview
> User's View:
![fb-ss-1](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/abf35067-6f87-4feb-9a10-310e07cd6b54)
![fb-ss-2](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/8509001b-13ed-4033-b17f-fb7d5c685eae)
![fb-ss-3](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/bec5c90c-e17d-4a16-a736-59461c884dc0)
![fb-ss-4](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/47ea011b-69dd-485b-b8c7-4ce80f56463c)

----
> Admin's View:
![fb-ss-5](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/dd4556ea-619c-41ee-a1bb-b40239919de7)
![fb-ss-6](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/940f5154-47ba-4899-a3b6-e3f32c9444fc)
![fb-ss-7](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/c2b9ea4e-88ca-478c-a4cd-85f0878a4631)
![fb-ss-8](https://github.com/Veluthil/Blog-with-users-Flask/assets/108438343/24317e7f-458f-41e9-982f-71086d8cc685)


## Installation
1. Clone the repository: `git clone https://github.com/Veluthil/Blog-with-users-Flask.git`
2. Change directory into the project folder
3. Create virtual environment: `py -m venv venv` `venv/Scripts/activate`
4. Install the required packages: `pip install -r requirements.txt`
5. Create a PostgreSQL database.
6. Change environmental variables to your own database URL and email credentials.
7. Run the application
