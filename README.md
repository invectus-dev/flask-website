## 📈 Project Status

![Progress](https://img.shields.io/badge/Progress-40%25-orange?style=for-the-badge)

The project is in early development. Current progress includes:

- ✅ Basic Flask setup
- ✅ Modular blueprint structure
- ✅ Route
- ✅ Make a frontend ( Jinja, Boostrap )
- ❌ Email verification
- ❌ Admin dashboard
- ❌ Unit tests
- ❌ Deployment configuration
- Etc...

Estimated completion: **40%**


# Flask Website 🚀

A fully functional Flask-based website with user authentication, database support, and clean modular design — inspired by [Tech With Tim's Flask Tutorial](https://youtu.be/dam0GPOAvVI).

---

## 📺 Tutorial Reference

This project is based on the YouTube tutorial by Tech With Tim:  
🔗 [Watch here](https://youtu.be/dam0GPOAvVI)

---

## 📁 Project Structure

```

flask-website/
├── app/
│   ├── **init**.py       # App factory
│   ├── auth.py           # Authentication routes
│   ├── views.py          # Main routes
│   ├── models.py         # SQLAlchemy models
│   └── templates/        # HTML templates
│       ├── base.html
│       ├── home.html
│       ├── login.html
│       └── signup.html
├── static/               # Static files (CSS, JS, etc.)
├── instance/
│   └── config.py         # Configuration settings
├── requirements.txt      # Python dependencies
└── run.py                # Entry point

````

---

## ⚙️ Features

- ✅ User Registration & Login
- ✅ Secure password hashing
- ✅ Protected routes with Flask-Login
- ✅ SQLite database with SQLAlchemy
- ✅ Bootstrap-styled frontend
- ✅ Modular Flask blueprints

---

## 📦 Requirements

- Python 3.8+
- pip (Python package manager)

---

## 🛠️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/invectus-dev/flask-website.git
cd flask-website
````

2. **Create a virtual environment**

```bash
python -m venv venv
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate          # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Configure environment**

Create a `config.py` inside the `instance/` directory:

```python
# instance/config.py

SECRET_KEY = 'your-secret-key'
SQLALCHEMY_DATABASE_URI = 'sqlite:///db.sqlite3'
```

5. **Run the app**

```bash
python run.py
```

than Visit: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## ✅ Usage

* Go to `/auth/signup` to create a new user.
* Log in via `/auth/login`.
* Access protected routes like `/` after logging in.
* Logout via `/auth/logout`.

---

## 🧩 Customization Ideas

* Add user profiles
* Create a blog system
* Add email verification
* Use PostgreSQL or MySQL
* Deploy with Gunicorn + Nginx or Render

---

## 🙌 Credit

This project follows the structure taught by Tech With Tim:
📹 **[Python Flask Website Full Tutorial](https://youtu.be/dam0GPOAvVI)**

---



