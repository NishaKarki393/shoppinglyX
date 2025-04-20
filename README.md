# 🛍️ shoppinglyX

**shoppinglyX** is a simple eCommerce web application built with Django. It allows users to browse products, add them to the cart, and proceed to checkout — all within a clean and responsive interface.

---

## 🌟 Features

- 🧾 Product browsing and listing
- 🛒 Add-to-cart functionality
- 🎯 Dynamic homepage with product highlights
- 💻 Responsive layout using Bootstrap
- 📁 Organized static files and templates

---

## 🧰 Tech Stack

- **Backend:** Django
- **Frontend:** HTML, CSS (Bootstrap), JavaScript
- **Database:** SQLite
- **Static Files:** Managed via Django staticfiles

---

## 📦 Installation

Follow the steps below to set up the project locally:

```bash
# Clone the repository
https://github.com/NishaKarki393/shoppinglyX.git

# Set up virtual environment (optional but recommended)
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the development server
python manage.py runserver
