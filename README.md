# 🛒 Online Auction Platform (Django)

An online auction website built with Django where users can create listings, place bids, comment, and manage a personal watchlist.

---

## 📌 Features

- 🧾 User registration, login, and logout
- 🛍️ Create, view, and manage auction listings
- 💰 Place bids on active listings
- 💬 Comment on listings
- 📂 Filter listings by categories
- 👁️ Add/remove listings from a personal watchlist
- 🔐 Close auctions and declare winners

---

## ⚙️ Technologies Used

- **Python 3.x**
- **Django Web Framework**
- **SQLite** (default database)
- HTML/CSS (basic styling)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```

### 2. Set up a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install dependencies

```bash
pip install -r requirements.txt  # Create this if not included
```

### 4. Run database migrations

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

Then open `http://127.0.0.1:8000` in your browser.

---

## 📁 Project Structure

```
commerce/            # Main Django project folder
  └── settings.py
  └── urls.py

auctions/            # Main application
  └── models.py
  └── views.py
  └── urls.py
  └── templates/
  └── static/

db.sqlite3           # Default SQLite database
manage.py            # Django management script
```

---

## 🧪 Sample Admin Login (Optional)

Create a superuser to manage listings via the admin panel:

```bash
python manage.py createsuperuser
```

Then visit `/admin` on your browser.

---

## ✍️ Author

Developed by **Nadiro97**
