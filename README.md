# Blog-with-users-Flask

I made this blog project in Python with the Flask framework and Bootstrap. The database is created in SQLite with the 
help of SQLAlchemy - passwords are hashed (sha256) and salted to protect sensitive data.
My project includes an admin account, which is why some functionalities (adding new posts, editing existing posts, 
deleting posts and comments) are disabled and hidden from regular users. All the routes for those functions are 
forbidden for non-admin clients to avoid accessing them via URL.
Commenting is available only for registered and logged-in users.
Tab 'Contact' allows all the viewers to send an email form to my inbox (smtplib module, SMTP protocol).

With cybersecurity in mind, an algorithm parses each client's HTML input. It sanitizes tags, attributes, unescaped 
characters, and unclosed and misnested tags.

I deployed this project on render.com: 
https://martyna-blog.onrender.com

This project is still unfinished, as I want to add other functionalities.

