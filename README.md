# 🍽️ Online Food Ordering & Integrated Stock Management System

A full-stack academic web application for online food ordering, restaurant/menu management, customer accounts, and order administration.

> Bachelor's in Computer Science & Engineering
> Currently pursuing Master's in Data Science at TU Wien
> Developer: Sri Sai Lokesh 

## 📌 Project Overview

This project was developed as an online food-ordering platform using **PHP, MySQL/MariaDB, HTML, CSS, JavaScript, and Bootstrap**.

The system provides two main sides:

- **Customer side** — browse restaurants and dishes, register/login, add food to the cart, place orders, view order history, and track order status.
- **Admin side** — manage restaurants, categories, menu items, users, and orders through an administrative dashboard.

The project also includes database support for restaurants, food dishes, users, orders, and order remarks/status updates.

## ✨ Main Features

### Customer
- User registration and login
- Browse restaurants and food items
- Filter restaurants/food
- Add dishes to cart
- Checkout and place orders
- View personal orders
- View order status
- Delete/cancel orders where supported

### Admin
- Admin authentication
- Dashboard
- Restaurant management
- Food category management
- Food menu management
- Customer management
- Order management
- Update order status
- View order details
- Order/earnings overview

## 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | PHP |
| Database | MySQL / MariaDB |
| UI assets | Bootstrap, Font Awesome and project CSS/JS assets |
| Development | Local PHP server such as XAMPP/WAMP |

## 📂 Repository Structure

```text
online-food-ordering-stock-management/
├── admin/                 # Admin dashboard and management pages
├── connection/            # Database connection configuration
├── css/                   # Frontend stylesheets
├── fonts/                 # Font assets
├── images/                # UI and food images
├── js/                    # JavaScript and frontend libraries
├── scss/                  # SCSS source
├── DATABASE FILE/         # Database schema/sample catalog data
├── *.php                  # Customer-facing application pages
├── LICENSE
├── .gitignore
└── README.md
```

## 🗄️ Database

Database name used by the application:

```text
onlinefoodphp
```

The repository includes:

```text
DATABASE FILE/onlinefoodphp.sql
```

The SQL file has been prepared for public sharing by removing seeded account/order/remark records that are unnecessary for a public GitHub repository.

### Main database areas

- `admin`
- `dishes`
- `remark`
- `restaurant`
- `res_category`
- `users`
- `users_orders`

## 🚀 Run Locally

### 1. Install a local PHP environment

You can use XAMPP, WAMP, or another local PHP + MySQL/MariaDB environment.

### 2. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/online-food-ordering-stock-management.git
cd online-food-ordering-stock-management
```

### 3. Create the database

Create:

```text
onlinefoodphp
```

Then import:

```text
DATABASE FILE/onlinefoodphp.sql
```

### 4. Configure the database connection

Open:

```text
connection/connect.php
```

Set the username/password for your local database server.

### 5. Start the application

Place the project inside your web server's document root, for example:

```text
XAMPP/htdocs/online-food-ordering-stock-management
```

Start Apache and MySQL/MariaDB, then open the project through your local server.

## 🔐 Security Note

This repository is intended for **academic/portfolio use**.

- Do not upload production database credentials.
- Do not commit API keys or private tokens.
- The public SQL dump does not include seeded customer/admin account records.
- The original application uses MD5 password hashing; for a production application, passwords should be migrated to a modern password-hashing approach such as PHP's `password_hash()` / `password_verify()`.

## 🎓 Academic / Portfolio Context

This project demonstrates practical experience with:

- Web application development
- PHP backend development
- Relational database design
- CRUD operations
- Authentication flows
- Shopping-cart/order workflows
- Admin dashboards
- Database-backed application logic

It also provides a foundation for future work combining software engineering with the user's current **Master's studies in Data Science**.

## 🔭 Possible Future Improvements

- Replace MD5 password hashing with secure password hashing
- Add prepared statements throughout the application
- Improve input validation and output escaping
- Add automated tests
- Improve API/backend separation
- Add analytics dashboards for orders and revenue
- Add data-analysis/ML features such as demand forecasting or recommendation systems
- Containerize the application with Docker
- Upgrade legacy PHP dependencies/code patterns

## 👨‍💻 Author

**Sri Sai Lokesh**  
B.E. Computer Science & Engineering  
Currently Master's Student in Data Science — TU Wien

---

⭐ If you find this project useful for learning, feel free to fork it and improve it.
