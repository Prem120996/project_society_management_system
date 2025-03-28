# 🏢 Society Management System

A **web-based Society Management System** developed using **PHP & MySQL** to facilitate efficient management of housing societies. It helps administrators handle residents, payments, maintenance requests, complaints, and announcements seamlessly.

## ✨ Features

- ✅ **Resident Management** – Add, update, and remove residents.
- ✅ **Maintenance Tracking** – Log and monitor maintenance requests.
- ✅ **Payment Management** – Manage society dues and payments.
- ✅ **Complaint System** – Residents can submit and track complaints.
- ✅ **Notice Board** – Admins can post important announcements.
- ✅ **Secure Authentication** – Login system for residents and admins.

## 🔧 Tech Stack

- **Frontend:** HTML, CSS, JavaScript (Bootstrap)
- **Backend:** PHP (PDO for secure database interactions)
- **Database:** MySQL
- **Server:** Apache (XAMPP) 

## 📂 Installation Guide

### 1. Clone the Repository
```bash
git clone https://github.com/Prem120996/project_society_management_system
.git
```

### 2. Import Database
- Open **phpMyAdmin**.
- Create a database named **sms1**.
- Import the `__.sql` file located in the `database/` folder.

### 3. Configure Database Connection
- Open `config.php` and update database credentials:
```php
```

### 4. Start XAMPP Services
- Run **Apache** and **MySQL** from the XAMPP Control Panel.

### 5. Run the Application
- Open a web browser and go to:
```
http://localhost/society_management_system/
```

## 🔐 User Roles

| Role   | Accessible Features |
|--------|---------------------|
| **Admin** | Manage residents, payments, maintenance, notices, complaints |
| **Resident** | View payments, submit complaints, check notices |


## 💪 Contributing

1. **Fork** the repository.
2. **Create a new branch:**
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit changes and push:**
   ```bash
   git commit -m "Added new feature"
   git push origin feature-branch
   ```
4. **Submit a pull request!**

## 📚 License

This project is **open-source** and available under the [MIT License](LICENSE).

