
# 🍽️ **Mealmate - Online Food Ordering System**  

> **A Django-based food ordering system where restaurant owners manage their menus, and customers can browse, order, and pay securely via Razorpay.**  

![Mealmate Banner](https://source.unsplash.com/1200x400/?food,restaurant)  

---

## 🚀 **Features**  

🔒 **Authentication**  
✅ User registration & login (for restaurant owners & customers)  
✅ Secure authentication using Django’s built-in system  

🏪 **Restaurant Management**  
✅ Add, edit & delete restaurants  

🍽️ **Menu & Orders**  
✅ Browse restaurant menus 🏀  
✅ Add items to the cart 🛒  
✅ Place orders 🛋️  

💳 **Payment Integration**  
✅ **Razorpay** for secure online payments  

---

## ⚙️ **Installation & Setup**  

### 1️⃣ **Clone the Repository**  
```sh
git clone https://github.com/your-username/mealmate.git
cd mealmate
```

### 2️⃣ **Set Up a Virtual Environment**  
```sh
python3 -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows
```

### 3️⃣ **Install Dependencies**  
```sh
pip install -r requirements.txt
```

### 4️⃣ **Apply Migrations**  
```sh
python manage.py migrate
```

### 5️⃣ **Create a Superuser**  
```sh
python manage.py createsuperuser
```

### 6️⃣ **Run the Development Server**  
```sh
python manage.py runserver
```
🔗 Now, open your browser and go to **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**  

---

## 📂 **Project Directory Structure**  
```
mealmate/
│── delivery/
│   │── migrations/
│   │── static/
│   │── templates/delivery/
│   │   ├── add_res.html
│   │   ├── base.html
│   │   ├── checkout.html
│   │   ├── cusmenu.html
│   │   ├── customer_home.html
│   │   ├── display_res.html
│   │   ├── failed.html
│   │   ├── index.html
│   │   ├── menu.html
│   │   ├── orders.html
│   │   ├── show_cart.html
│   │   ├── sign_in.html
│   │   ├── sign_up.html
│   │   ├── success.html
│   │   ├── userdata.html
│   │── __init__.py
│   │── admin.py
│   │── apps.py
│   │── forms.py
│   │── models.py
│   │── tests.py
│   │── views.py
│── manage.py
│── requirements.txt
```

---

## 🌐 **API Endpoints (Django REST Framework)**  

| **Method** | **Endpoint**                | **Description**                |
|-----------|----------------------------|--------------------------------|
| GET       | `/restaurants/`            | List all restaurants          |
| POST      | `/restaurants/add/`        | Add a new restaurant          |
| PUT       | `/restaurants/update/<id>/` | Update restaurant details     |
| DELETE    | `/restaurants/delete/<id>/` | Delete a restaurant           |
| GET       | `/menu/`                   | Get menu items                |
| POST      | `/order/`                   | Place an order                |

---

## 💳 **Razorpay Payment Integration**  

1️⃣ **Sign up** at [Razorpay](https
