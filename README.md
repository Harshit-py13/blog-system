<img width="1755" height="1617" alt="image" src="https://github.com/user-attachments/assets/382b4db2-5c50-4b69-8a99-e791f38dc986" /># 📰 Django Blog / News Management System

A full-stack **Django-based Blog & News Management System** that allows users to read articles by category, search posts, and interact through comments. It also includes an **admin dashboard** for managing posts and categories efficiently.

---

## 🚀 Features

### 👤 User Features
- 📄 View blog/news articles with images
- 🔍 Search posts by keywords
- 🗂️ Browse posts by categories (Sports, Politics, Technology, Science, Health, Business)
- 💬 Add comments on posts
- 📅 Display post publish date and author
- 📱 Responsive UI using Bootstrap

### 🛠️ Admin / Dashboard Features
- 🔐 User authentication (Login / Logout)
- 📊 Admin dashboard overview
- 🗂️ Create, update, and delete categories
- 📝 Create, edit, and delete posts
- 🖼️ Upload images for posts
- 👥 Manage users

---

## 🖥️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite3
- **Authentication:** Django built-in auth system
- **Version Control:** Git & GitHub
- **Deployment:** PythonAnywhere *(can be extended to AWS / Render / Railway)*

## ⚙️ Installation & Setup (Local)

1. **Clone the repository**
   
   git clone https://github.com/Harshit-py13/blog-system.git
   cd blog-system
   
2. Create & activate virtual environment

python -m venv env
env\Scripts\activate   # Windows

3. Install dependencies

pip install -r requirements.txt

4. Run migrations

python manage.py makemigrations
python manage.py migrate

5. Create superuser

python manage.py createsuperuser

6. Run the server

python manage.py runserver

7. Open in browser:

http://127.0.0.1:8000/
