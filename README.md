Django Blog News System
A full-stack, dynamic blogging and news platform built with Django. This project features category-based content management, a robust search engine, and a secure user interaction system.

Live Demo: https://Harshit12.pythonanywhere.com

🚀 Features

Dynamic Categorization: Automatically filters and serves blog posts based on taxonomies like Sports, Politics, Technology, etc.
+1


Advanced Search: Built using Django Q objects to perform complex, multi-field queries across titles and content.


User Engagement: Integrated authentication system allowing users to register, login, and leave comments on posts.
+1


Production Ready: Fully deployed on PythonAnywhere with configured HTTPS security and static/media file handling.


Responsive UI: Designed with Bootstrap 5 for a seamless experience on both mobile and desktop devices.
+1

🛠️ Tech Stack

Backend: Python 3.13, Django.
+2


Frontend: HTML5, CSS3, Bootstrap 5.
+1


Database: SQLite3.


Deployment: PythonAnywhere.

📦 Installation & Setup
Clone the repository:

Bash

git clone https://github.com/Harshit-py13/blog-system.git
cd blog-system
Create and activate a virtual environment:

Bash

# For Windows
python -m venv venv
.\venv\Scripts\activate

# For Mac/Linux
python3 -m venv venv
source venv/bin/activate
Install dependencies:

Bash

pip install -r requirements.txt
Run migrations and start the server:

Bash

python manage.py migrate
python manage.py runserver
🔒 Security & Optimization

Environment Variables: Configured to automatically toggle DEBUG settings between Local and Production environments.


Error Handling: Implemented custom 404 error pages to improve site reliability and user experience.


Security: Enforced Force HTTPS and secure static file mapping for production.
