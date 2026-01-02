# 💰 Smart Expense Tracker

A web-based application built with **Django** and **MySQL** to help users track their daily expenses, manage their budget, and visualize their spending habits.

## 🚀 Features
* **User Authentication:** Secure Login and Registration system.
* **Dashboard:** View total balance and recent transactions.
* **Add Expenses:** Easily record daily spending.
* **Profile Management:** Manage user details.
* **Secure Database:** Uses MySQL for robust data storage.

## 🛠️ Tech Stack
* **Backend:** Python, Django
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript
* **Authentication:** Django Auth System

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/expense-tracker.git](https://github.com/YOUR_USERNAME/expense-tracker.git)
cd expense-tracker

pip install -r requirements.txt

CREATE DATABASE expense_tracker;

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'expense_tracker',
        'USER': 'root',
        'PASSWORD': 'YOUR_MYSQL_PASSWORD',  # <--- Update this
        'HOST': 'localhost',
        'PORT': '3306',
    }
}

python manage.py migrate
python manage.py runserver
EMAIL_HOST_USER = 'your-email@gmail.com'
EMAIL_HOST_PASSWORD = 'your-app-password'
