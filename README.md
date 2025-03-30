# 👨‍💼 Employee Details Management System

## 📌 Introduction
The **Employee Details Management System** is a web-based application designed to manage employee records efficiently. It allows HR departments to add, update, and track employee details, ensuring smooth workforce management.

## 🚀 Features
- 🔑 **Secure Authentication** – Role-based access for HR, Admins, and Employees
- 📋 **Employee Records Management** – Add, update, and delete employee details
- 📊 **Reports & Analytics** – Generate employee statistics and reports
- 📩 **Notifications & Alerts** – Get alerts for birthdays, anniversaries, and upcoming leaves

## 🏗 Project Structure
```
employee_management/
│── employeerecord/                      # Django projectname
│   ├── _init_.py/         
│   ├── adminview.py/         
│   ├── asgi.py/
│   ├── empviews.py
│   ├── settings.py/       
│   ├── urls.py/         
│   ├── views.py/
│   ├── wsgi.py
│
│── ersapp/
│   ├── _init_.py/         
│   ├── admin.py/         
│   ├── apps.py/
│   ├── models.py
│   ├── tests.py/         
│   ├── views.py/         


```

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```
git clone https://github.com/NandiniReddy9/small-employee-record-sys.git
cd employee-management
```
### 2️⃣ Install Dependencies & Setup Environment
```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
### 3️⃣ Run Migrations & Start Server
```
python manage.py migrate
python manage.py runserver
```
### 4️⃣ Run ersapp (Optional for React)
```
cd ersapp
npm install
npm start
```

## 🖥 API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | `/api/auth/register/` | Register a new employee |
| POST | `/api/auth/login/` | Employee login |
| GET | `/api/employees/` | Retrieve all employees |
| POST | `/api/employees/add/` | Add a new employee |
| PATCH | `/api/employees/{id}/` | Update employee details |
| DELETE | `/api/employees/{id}/` | Remove an employee |

## 📌 Status Codes
| Status Code | Meaning |
|------------|---------|
| 200 OK | Request successful |
| 201 Created | New resource created |
| 400 Bad Request | Invalid input |
| 401 Unauthorized | Authentication failed |
| 404 Not Found | Resource not found |

## 🚀 Deployment Guide
- Modify `.env` with production credentials


## 📞 Contact & Support
- 📧 Email: support@employeemanagement.com
- 🌐 Website: [www.employeemanagement.com](https://www.employeemanagement.com)



---
### 💡 Simplify Employee Management with Ease! 🚀

