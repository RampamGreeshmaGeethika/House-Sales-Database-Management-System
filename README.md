# House-Sales-Database-Management-System
A MySQL-based real estate management system with PHP/XAMPP, implementing optimized database design and secure CRUD functionality. Created a responsive dashboard with role-based access and visual analytics for improved reporting and decision-making.

Here is a **professional README.md** you can use for your **House Sales Database Management System** GitHub repository. You can copy and paste this directly into your repo.

---

# 🏠 House Sales Database Management System

A full-stack **real estate management system** designed to streamline property listings, offers, rentals, payments, and customer interactions. The system provides role-based access for buyers, sellers, agents, and administrators while ensuring secure transactions and efficient data management.

---

# 📌 Overview

The **House Sales Database Management System** is built to simplify the real estate process by enabling users to:

* List and manage property sales and rentals
* Schedule appointments for property visits
* Submit and manage property offers
* Process payments securely
* Track property ownership and rental contracts
* Manage support tickets and user activity logs

The system integrates a **normalized relational database (MySQL)** with a web application interface built using **PHP and XAMPP**, supporting robust CRUD operations and optimized query performance.

---

# 🚀 Features

### 👤 User Management

* Role-based access control for:

  * Buyer
  * Seller
  * Agent
  * Admin
* Secure authentication with password hashing
* Unique email-based user identification

### 🏡 Property Listings

* Create, update, and delete property listings
* Track property availability status
* Upload property images

### 📅 Appointment Scheduling

* Buyers can schedule property visits
* Agents/Sellers can accept or reject appointment requests

### 💰 Offer Management

* Buyers and agents can submit property offers
* Only one active offer per user per property
* Automatic rejection of competing offers when one is accepted

### 💳 Payment Processing

* Payments allowed only for accepted offers
* Automatic update of property status to **Sold**

### ⭐ Favorites

* Users can save favorite properties for quick access

### 📄 Rental Management

* Create and manage rental contracts
* Track rental interest and payment status

### 🎫 Support Ticket System

* Users can submit support tickets
* Admins can resolve issues with recorded resolutions

### 📊 Audit Logging

* Logs all user actions for traceability
* Tracks activities such as offers submitted, payments processed, etc.

---

# 🗄 Database Design

The system uses a **normalized relational database schema** designed to ensure data integrity and efficient queries.

### Core Tables

* Users
* Property_Listings
* Property_Images
* Appointments
* Offers
* Payments
* Favorites
* Tickets
* Audit_Log
* Rental_Contracts
* Rental_Interest

The schema enforces:

* Foreign key constraints
* Data validation rules
* Role-based permissions
* Transaction consistency

---

# 🛠 Tech Stack

### Backend

* PHP

### Database

* MySQL

### Server Environment

* XAMPP

### Frontend

* HTML
* CSS
* JavaScript

### Tools

* phpMyAdmin
* Git & GitHub

---

# ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/house-sales-dbms.git
cd house-sales-dbms
```

---

### 2️⃣ Install XAMPP

Download and install XAMPP:

[https://www.apachefriends.org/](https://www.apachefriends.org/)

Start the following services:

* Apache
* MySQL

---

### 3️⃣ Setup the Database

1. Open **phpMyAdmin**
2. Create a database:

```sql
CREATE DATABASE house_sales_db;
```

3. Import the provided SQL file:

```
database/house_sales_db.sql
```

---

### 4️⃣ Run the Application

Move the project folder to:

```
xampp/htdocs/
```

Open browser and run:

```
http://localhost/house-sales-dbms
```

---

# 📊 System Workflow

1️⃣ Users register and log in to the system
2️⃣ Sellers or agents create property listings
3️⃣ Buyers browse properties and schedule visits
4️⃣ Buyers submit offers on available properties
5️⃣ Sellers accept or reject offers
6️⃣ Accepted offers proceed to payment processing
7️⃣ Property status updates to **Sold**

you create a **much stronger GitHub README with badges, architecture diagrams, and project screenshots** so it looks **professional to recruiters and hiring managers.**
