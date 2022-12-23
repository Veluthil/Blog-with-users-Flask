# Blog-with-users-Flask

This blog project was written in Python with the usage of Flask framework and Bootstrap. The database was created in SQLite with help of SQLAlchemy - passwords before storing are 
hashed (sha256) and salted to protect sensitive data.
My project includes an admin account, therefore some functionalities (adding new posts, editing existing posts, deleting posts and comments) are disabled and hidden from regular users. All the routes for those functions are forbidden for non-admin clients to avoid accessing them via URL.
Commenting is available only for registered and logged-in users.
Tab 'Contact' allows all the viewers to send an email form to my inbox (smtplib module, SMTP protocol).

Bearing in mind cybersecurity every HTML input provided by clients is parsed by an algorithm which
sanitizes tags, attributes, unescaped characters, unclosed and misnested tags.

I deployed this project on render.com, here is the URL: 
https://martyna-blog.onrender.com

This project is still not finished as I want to add further functionalities.

