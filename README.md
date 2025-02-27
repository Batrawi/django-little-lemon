# 🍋 Little Lemon - Django Restaurant Menu App

[![Django](https://img.shields.io/badge/Django-4.2-green.svg)](https://www.djangoproject.com/)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)

Little Lemon is a Django-based web application that allows restaurants to manage their menus and display them to customers. The project includes an **admin panel**, **dynamic menu listings**, and **user-friendly navigation**.

---

## 🚀 Features
✅ Dynamic menu page listing food items 🍽️  
✅ Django admin panel for menu management 🔑  
✅ Template-based rendering with **Django Template Language (DTL)** 🎨  
✅ SQLite3 database for storing menu items 🗄️  
✅ Secure authentication system for admin 🔒  

---

## 📸 Screenshots
### 🏠 **Home Page**
![Home page](https://github.com/GergesHany/Little-Lemon/assets/105644935/ed14c250-a77c-4f11-bd07-c7aeb5898210)

### 📜 **Menu Page**
![Screenshot from 2023-11-18 20-13-56](https://github.com/GergesHany/Little-Lemon/assets/105644935/655d249c-ab6b-42dc-9b09-a0e921144518)

---

## 🛠️ Installation Guide

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/your-username/Little-Lemon.git
cd Little-Lemon
```

### **2️⃣ Create and Activate a Virtual Environment**
```sh
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### **3️⃣ Install Dependencies**
```sh
pip install -r requirements.txt
```

### **4️⃣ Apply Database Migrations**
```sh
python manage.py migrate
```

### **5️⃣ Create a Superuser (Admin)**
```sh
python manage.py createsuperuser
```

### **6️⃣ Run the Development Server**
```sh
python manage.py runserver
```
Now, visit **http://127.0.0.1:8000/** in your browser! 🎉

---

## 📂 Project Structure
```
Little-Lemon/
│-- restaurant/
│   │-- templates/
│   │   │-- menu.html
│   │   │-- menu_item.html
│   │-- views.py
│   │-- models.py
│   │-- urls.py
│-- db.sqlite3
│-- manage.py
│-- venv/
│-- README.md
```

---

## ✨ Credits
Developed with ❤️ by [Mohammed Albattrawi](https://github.com/batrawi)  
Inspired by the [Meta Backend Developer Course](https://www.coursera.org/professional-certificates/meta-backend-developer)
