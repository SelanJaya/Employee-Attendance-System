# Employee Attendance Management System

## 📌 Overview

The Employee Attendance Management System is a web-based application developed to improve the efficiency, accuracy, and reliability of employee attendance tracking at Universiti Malaysia Terengganu (UMT). The system replaces traditional punch card methods with a centralized digital solution, enabling real-time monitoring, improved data accuracy, and reduced manual errors.

The system is designed using the Model-View-Controller (MVC) architecture and supports key functionalities such as attendance tracking, leave management, overtime processing, and reporting.

---

## 🛠️ Tech Stack

* Java (Servlet, JSP)
* MySQL
* Apache Tomcat 9
* HTML, CSS

---

## ✨ Features

* User Profile Management (view and update personal information)
* Attendance Management (clock in/out, attendance tracking)
* Disciplinary Notice System for attendance issues
* Overtime Request and Approval System
* Leave Application and Approval System
* Department-based attendance management (Head of PTJ)
* Attendance reporting and monitoring

---

## ⚙️ Non-Functional Requirements

* Efficient handling of concurrent users
* Secure data handling and protection
* User-friendly interface with simple navigation
* Cross-platform and multi-device compatibility
* Maintainable system using MVC architecture

---

## 🚀 How to Run

### 1. Requirements

* Apache Tomcat 9
* MySQL
* NetBeans IDE (recommended)

### 2. Database Setup

1. Create database:

   ```
   attendancesystem1_db
   ```

2. Import SQL file:

   ```
   database/attendancesystem1_db.sql
   ```

3. Configure database connection (if needed):

   * Update DB credentials in your Java file (e.g., DBConnection.java)

---

### 3. Run the Project

1. Open the project in NetBeans
2. Right-click project → Run
3. Access the system:

   ```
   http://localhost:8080/testLogin
   ```

---
## 📸 Screenshots

### 🔐 Login Page

![Login](https://github.com/user-attachments/assets/7dc7edf9-9ede-4fdd-8ad5-922eba2c0b8e)

---

### 📊 Dashboard (Role-Based Views)

![HR Dashboard](https://github.com/user-attachments/assets/435f6235-527b-4056-b10e-36f6f7d26f04)

<br>

![PTJ Dashboard](https://github.com/user-attachments/assets/901e1ff0-be81-48f8-b1d6-d36f7b14c0b2)

<br>

![Academician Dashboard](https://github.com/user-attachments/assets/3f6eca75-b64b-446a-9cf1-e2fca078151e)

<br>

![Supporting Staff Dashboard](https://github.com/user-attachments/assets/b0fa9b30-6a1f-455b-bc77-6493c72cbaf2)

---

### ⏱️ Attendance System

#### 🧑‍🏫 Academician – Clock In / Out

![Academician Attendance](https://github.com/user-attachments/assets/bc1fab63-a265-492b-b766-b7f60075cc19)

<br>

#### 👩‍💼 Supporting Staff – Attendance & History

![Staff Attendance](https://github.com/user-attachments/assets/e9aa6f93-582a-4d37-8a4b-f28971963e3d)

<br>

![Attendance History](https://github.com/user-attachments/assets/73c73eb3-9d51-4c95-b26e-358844559f2c)

<br>

#### 👨‍💼 HRD – Approval & Records

![HR Approval](https://github.com/user-attachments/assets/c051947e-1d16-4456-b4cc-6368f28fdc74)

<br>

![PTJ View](https://github.com/user-attachments/assets/ae05a4f7-465b-4118-a135-88ad005c7a05)

---

### ⏳ Overtime Management

#### 👩‍💼 Supporting Staff – Submit Request

![Overtime Form](https://github.com/user-attachments/assets/f9912316-49a6-4e3a-acf6-31e1f3bcc21d)

<br>

#### 🏢 Head of PTJ – Review Requests

![Overtime List](https://github.com/user-attachments/assets/7f6e7c71-62e0-45a4-8628-ebe3e1ad6ab9)

<br>

#### 🏢 Head of PTJ – Approve / Reject

![Overtime Approval](https://github.com/user-attachments/assets/7ef0928b-05ba-4545-bc4f-5cd6d2435edb)

---

### 📝 Leave Management

#### 🧑‍🏫 Academician – Apply Leave

![Leave Form](https://github.com/user-attachments/assets/e0f52a82-4073-4515-8b1c-8496abc10547)

<br>

#### 👩‍💼 Supporting Staff – View Applications

![Leave List](https://github.com/user-attachments/assets/9191d6fd-1d35-4435-880c-8db8ec1df976)

<br>

#### 🏢 Head of PTJ – Approve / Reject

![Leave Approval](https://github.com/user-attachments/assets/8c833d77-6975-47cf-a700-90e35c96e5c6)

---

### 📈 Reporting System

#### 👨‍💼 HRD – Generate Report

![Report Input](https://github.com/user-attachments/assets/5cf6654b-908c-4e4f-8003-4d602e3c9b7e)

<br>

#### 📊 Report Output

![Report Output](https://github.com/user-attachments/assets/95bd25b6-d8c1-4dbc-9cf5-ddf828d00561)

---

💡 **Note:** Additional user interfaces and system features can be explored by running the application locally.

---

## 🔐 Sample Credentials

| Role              | Username | Password  |
|-------------------|----------|-----------|
| HRD               | azhar    | azhar123  |
| Academician       | najmi    | najmi     |
| Supporting Staff  | mat      | mat       |
| Head of PTJ       | aimi     | azhar123  |

## ⚠️ Notes

* This project was developed as part of coursework
* Some improvements (e.g., optimization, error handling) can be further enhanced
