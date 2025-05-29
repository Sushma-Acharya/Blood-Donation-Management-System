# Blood Donation Management System

A web-based application built to streamlines and manages blood donor records, patient requests, and inventory tracking for blood banks using a structured relational database.

## 🧠 Project Overview

This Blood Donation Management System (BDMS) aims to automate core blood bank operations including:

- Donor and patient management
- Blood inventory tracking
- Request handling
- Role-based access for admins, donors, and patients

The system ensures efficiency, data integrity, and real-time monitoring, thus aiding in emergency responsiveness and reducing administrative overhead.

## 🔧 Tech Stack

| Layer      | Technology             |
|-----------|------------------------|
| Frontend  | HTML, CSS, JavaScript  |
| Backend   | PHP                    |
| Database  | MySQL                  |
| Server    | Apache (localhost:8080)|

## ✨ Features

- Donor and patient registration & login
- Blood request submission and approval system
- Real-time blood stock updates
- Admin dashboard to manage users and inventory
- Secure authentication and role-based access control

## 🔐 Database Design

### Key Entities:
- **Donors**: Stores donor details and history
- **Patients**: Manages patient data and requests
- **Donations**: Tracks donations and updates stock
- **Requests**: Handles patient blood requests
- **Stocks**: Maintains blood group-wise inventory

### ER Model & Relational Schema:
- Designed using entity-relationship principles
- Normalized up to BCNF to eliminate redundancy and maintain data integrity

## 🧪 API Endpoints (Sample)

```php
// Get all donors
GET /api/donors

// Register a new donation
POST /api/donations

// Submit a blood request
POST /api/requests
```




## 🖥️ Screenshots

- Home Page
  ![Image](https://github.com/user-attachments/assets/dc46f3f0-dec9-417c-abab-efc3fc9dd550) 
- Donor and Admin Dashboard
  ![Image](https://github.com/user-attachments/assets/8e66dd29-f8bb-419f-a688-0afe017ab219) 
- Blood Request Form
  ![Image](https://github.com/user-attachments/assets/1b32a27e-0206-4983-9e41-5dd128c4a23d)   
- Donor and Patient Record Management
  ![Image](https://github.com/user-attachments/assets/b6e65d1d-1528-4fbf-a907-b0885a0e3962)



## 🧪 How to Run

1. Clone the repository.
2. Set up the Apache server (XAMPP/LAMP).
3. Import the database schema in MySQL via phpMyAdmin.
4. Place the project files in the server directory (e.g.,
