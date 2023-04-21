# Blog-with-users-Flask

This is a Python-based blog project built using the Flask web framework and Bootstrap. The application uses a PostgreSQL database, which was created with the help of SQLAlchemy. Passwords are hashed and salted using sha256 to protect sensitive data.

The project includes an admin account, which has access to additional functionalities such as adding new posts, editing existing posts, deleting posts, and comments. These functionalities are disabled and hidden from regular users. The routes for these functions are forbidden for non-admin clients to prevent unauthorized access.

Registered and logged-in users can leave comments on the blog posts. The 'Contact' tab allows viewers to send an email form to the site owner's inbox using the smtplib module and SMTP protocol.

The project prioritizes cybersecurity by using an algorithm to sanitize each client's HTML input. The algorithm removes unwanted tags, attributes, unescaped characters, and unclosed or misnested tags.

The project is currently deployed on Render at https://martyna-blog.onrender.com. However, it is still unfinished, and I plan to add more functionalities in the future.
