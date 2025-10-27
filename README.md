# Food-Ordering-Website

# 🍔 Food Ordering Website
Remeber There are Several Error For Photo Uploading or few small things if you able to fix that Errors.
A complete **Food Ordering Web Application** built using **PHP, MySQL, HTML, CSS, and JavaScript**.  
This project allows users to explore food items, add them to the cart, and place orders online.  
It includes an **Admin Dashboard** for managing categories, foods, orders, and users efficiently.

---

## 🌟 Overview

This web application simulates a real-world food ordering system, designed for educational and demonstration purposes.  
It provides an interactive and responsive interface for both customers and administrators.

Users can register, log in, browse a food catalog, and place orders, while admins can manage everything through a secure admin panel.

---

## 🚀 Features

### 👨‍🍳 User Panel
- User Registration & Login System
- Browse Menu with Food Images and Prices
- Add, Update, or Remove Items from Cart
- Place Orders with Confirmation
- Responsive Design for All Devices
- View Order Status

### 🛠️ Admin Panel
- Secure Admin Login
- Manage Categories (Add/Edit/Delete)
- Manage Food Items (Add/Edit/Delete)
- Manage Users
- Manage Orders (View, Update Status)
- Dashboard Summary

### 🗄️ Database Features
- MySQL Database Integration
- Structured Tables for Users, Orders, Foods, and Categories
- Easy Database Import via SQL file

---

## 🧰 Technologies Used

| Component | Technology |
|------------|-------------|
| **Frontend** | HTML5, CSS3, JavaScript |
| **Backend** | PHP (Core PHP) |
| **Database** | MySQL |
| **Web Server** | Apache (via XAMPP/WAMP) |
| **Version Control** | Git & GitHub |

---

## 🗂️ Folder Structure

```
food-ordering-website/
├── actions/                # Backend scripts for user actions (login, cart, etc.)
├── admin/                  # Admin dashboard and management panels
│   ├── css/                # Admin-specific styles
│   ├── index.php           # Admin dashboard home
│   ├── manage-orders.php   # Manage orders page
│   ├── manage-foods.php    # Manage food items
│   ├── manage-users.php    # Manage user accounts
│   └── login.php           # Admin login page
├── css/                    # Website CSS files
├── database/               # Contains MySQL database file (.sql)
├── images/                 # Website images (logo, food items, etc.)
├── config.php              # Database configuration file
├── functions.php           # Common functions used throughout the project
├── index.php               # Main homepage
├── setup.php               # Setup script (initialization)
└── structure.txt           # Project structure reference
```

---

## ⚙️ Installation & Setup Guide

Follow these steps to run the project on your local machine:

download the ZIP file and extract it to your **htdocs** folder in XAMPP.

### 🗃️ 2. Set Up the Database
1. Open **phpMyAdmin** via [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
2. Create a new database, for example: `food_ordering`
3. Import the file located at:
   ```
   /database/food_ordering.sql
   ```

### ⚙️ 3. Configure Database Connection
Open `config.php` and verify the database credentials:
```php
<?php
$conn = mysqli_connect("localhost", "root", "", "food_ordering");
if (!$conn) {
  die("Database connection failed: " . mysqli_connect_error());
}
?>
```

### 🖥️ 4. Run the Application
- Open your browser and go to:  
  👉 [http://localhost/food-ordering-website/](http://localhost/food-ordering-website/)

- For Admin Panel:  
  👉 [http://localhost/food-ordering-website/admin/login.php](http://localhost/food-ordering-website/admin/login.php)

### 🔐 5. Admin Login Credentials
| Username | Password |
|-----------|-----------|
| admin     | admin123  |

> (You can modify this in your database under the `admin` table.)

---

## 🧑‍💻 Developer Notes

- Keep your **config.php** secure; never share credentials publicly.
- To change website logo or images, replace files in `/images/`.
- You can modify categories and foods via the Admin Dashboard.

---

## 💡 Future Enhancements
- Integrate online payment gateways (Stripe, Razorpay)
- Add email notifications for order confirmation
- Implement order tracking system
- Add coupon/discount system
- Improve UI/UX with a modern framework (Bootstrap or Tailwind)

---

## 🧑‍💻 Author

**Your Name**  
📧 ravimodhvadiya18@gmail.com
🌐 https://www.linkedin.com/in/ravi-modhvadiya-347a54344?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BDVy%2FJ1L5SE%2BO53qlOwcu8g%3D%3D

---

## 📜 License

This project is open source and available under the **MIT License**.  
Feel free to use and modify it for learning or development purposes.

---

## ❤️ Acknowledgements
- PHP & MySQL documentation  
- Free resources from [Unsplash](https://unsplash.com) and [Pexels](https://pexels.com) for food images  
- Open-source community for inspiration

---

> ⭐ If you like this project, don’t forget to star the repository on GitHub!
