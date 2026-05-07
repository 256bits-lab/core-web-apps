# 🏨 Hostel Booking System

A modern hostel reservation and management platform built under **256 Bits Lab**.

This system is designed to help students and hostel administrators manage room allocation, reservations, occupancy tracking, and bookings through a centralized digital platform.

---

# 🚀 Features

## 👤 User Features

* User registration & authentication
* Secure login/logout system
* Browse available rooms
* View room details and pricing
* Book hostel rooms online
* Booking status tracking
* User dashboard

---

## 🛠 Admin Features

* Admin authentication
* Add/edit/delete hostel rooms
* Manage users
* Approve or reject bookings
* Track occupancy
* Manage room availability
* View booking statistics

---

# ⚙️ Technology Stack

## Backend

* PHP (PDO)
* MySQL

## Frontend

* HTML5
* CSS3
* JavaScript

## Development Environment

* Windows
* Apache / Nginx
* Git & GitHub

---


# 🗄 Database Design

## Main Tables

* users
* admins
* rooms
* bookings
* payments

---

# 🔐 Security Features

* Password hashing using `password_hash()`
* PDO prepared statements
* Input validation & sanitization
* Session-based authentication
* Role-based access control

---

# 📌 Planned Features

* Mpesa payment integration
* Email notifications
* Booking receipts
* Room search & filtering
* Multi-hostel support
* REST API support

---

# ⚡ Installation

## 1. Clone Repository

```bash
git clone https://github.com/256bits-lab/core-web-apps.git
```

---

## 2. Navigate to Project

```bash
cd core-web-apps/hostel-booking-system
```

---

## 3. Setup Database

Create a MySQL database:

```sql
CREATE DATABASE hostel_booking_system;
```

Import:

```bash
database/schema.sql
```

---

## 4. Configure Database Connection

Edit:

```bash
config/database.php
```

Update:

* database username
* password
* database name

---

## 5. Run Project

Move project into your web server directory and run locally using:

* Apache
* XAMPP
* LAMP
* Laragon

---

# 🎯 Project Goals

This project aims to:

* simplify hostel management
* improve booking efficiency
* reduce manual paperwork
* provide scalable digital infrastructure

---

# 🌍 Vision

The Hostel Booking System is part of the broader **256 Bits Lab** initiative focused on building secure, scalable, and impactful software systems.

---

# 📜 License

MIT License

---

# 👨‍💻 Author

**256 Bits Lab**
Founder: Raynner Kavulika

> Built with discipline. Engineered for scale.

