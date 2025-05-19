# 🏨 Hotel Management System

A web-based Hotel Management System that streamlines the restaurant ordering process with separate interfaces for customers and managers. Customers can view the menu, add items to a dynamic cart, place orders, and enter payment details. Managers can manage the menu and monitor incoming orders.

---

## 🚀 Features

### 👤 Customer Side
- Customer login with unique ID
- View interactive, dynamic menu
- Add/remove items from cart
- View real-time total of selected items
- Place order and provide payment details

### 🧑‍💼 Manager Side
- Manager login
- View all customer orders
- Add new menu items
- Edit or remove existing menu items
- View ordered items and their quantities

---

## 🛠️ Tech Stack

- **Backend:** Django, Python
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default Django database)

---

## 💻 How to Run the Project Locally


   ```bash
   git clone https://github.com/Deepitha-P/Hotel_management/.git
   cd hotel-management
   python -m venv venv
   venv\Scripts\activate
   python manage.py migrate
   python manage.py runserver
   
