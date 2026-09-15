# Grand-coffee-cafe-management-system
A web-based Café Management System designed to digitize and simplify café operations. The system provides online menu browsing, user registration and login, cart and order handling, menu and category management, customer inquiries, and an admin dashboard using PHP, MySQL, HTML, CSS, JavaScript, and XAMPP.

# ☕ Grand Coffee Café Management System

## 📌 Project Overview

Grand Coffee Café Management System is a web-based application developed to digitize and simplify the daily operations of a café.

The system provides an easy-to-use platform where customers can explore café information, view menu items, check prices and descriptions, register/login, add items to a cart, and place orders.

The system also provides an Admin Panel through which the administrator can manage menu items, categories, orders, customer information, and other website operations.

The main purpose of this project is to reduce manual work, minimize errors, improve operational efficiency, organize café data, and provide a better experience for both customers and café administrators.

---

## 🎯 Goals and Objectives

The main goals of the project are:

- Automate basic café information and menu management.
- Reduce manual effort in managing menu items and categories.
- Provide clear and organized café and menu information.
- Provide an admin panel for managing café operations.
- Allow users to view menu items and prices easily.
- Provide user registration and login functionality.
- Provide cart and order handling.
- Maintain structured customer and menu data.
- Handle customer inquiries through the contact form.
- Improve café operational efficiency through a web-based system.

---

## ✨ Main Features

### 👤 User Module

Users/customers can:

- View the café homepage.
- Browse the café menu.
- View item names, prices and descriptions.
- Register an account.
- Login to the system.
- Add menu items to the cart.
- View cart items.
- Place orders.
- View order-related information.
- Submit inquiries through the contact form.

### 👨‍💼 Admin Module

The administrator can:

- Login to the Admin Panel.
- Manage café website operations.
- Add new menu items.
- Update menu item information.
- Delete unavailable or outdated menu items.
- Manage menu categories.
- Manage orders.
- View customer-related information.
- Handle customer messages and inquiries.
- Maintain database information.

### 🍵 Menu Management

The menu module provides:

- Menu item listing.
- Category-based organization.
- Item name.
- Price.
- Description.
- Menu management through the Admin Panel.

### 🛒 Cart and Order Module

The system supports:

- Adding items to cart.
- Viewing selected items.
- Order processing.
- Storing order information.
- Maintaining order-related records.

### 🔐 Authentication

The system provides:

- User registration.
- User login.
- Admin login.
- Login validation.
- Session management.
- Restricted admin access.

### 📩 Contact Management

Customers can submit:

- Name
- Email
- Subject
- Message

The administrator can manage customer inquiries through the system.

---

## ⚙️ How the System Works

The system follows a simple client-server architecture.

### Step 1 – User Opens Website

The customer opens the café website using a web browser.

### Step 2 – Browse Menu

The user can view café information and available menu items with prices and descriptions.

### Step 3 – Registration/Login

If required, the user can create an account and login to the system.

### Step 4 – Select Items

The customer selects the desired menu items.

### Step 5 – Add to Cart

Selected items are added to the shopping cart.

### Step 6 – Place Order

The customer reviews the cart and proceeds with the order.

### Step 7 – Database Storage

PHP processes the request and communicates with the MySQL database.

The system stores required information such as users, menu items and order-related records.

### Step 8 – Admin Management

The administrator logs into the Admin Panel and can manage:

- Menu
- Categories
- Orders
- Customer information
- Messages

### Step 9 – Database Update

Whenever the administrator adds, updates, or deletes information, the corresponding database records are updated.

---

## 🏗️ System Architecture

The project follows a basic three-part architecture:

```text
             👤 USER
                |
                ↓
        🌐 Web Browser
                |
                ↓
       ┌─────────────────┐
       │   PHP Backend   │
       │ Business Logic  │
       └─────────────────┘
                |
                ↓
       ┌─────────────────┐
       │ MySQL Database  │
       │   coffee_db     │
       └─────────────────┘
                |
                ↓
          📊 Admin Panel
