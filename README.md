<img width="1476" height="739" alt="image" src="https://github.com/user-attachments/assets/b6cc1b06-e440-45fd-af38-eee519409ac6" /><img width="1476" height="739" alt="image" src="https://github.com/user-attachments/assets/3c412b25-cc8d-48f6-88c1-a7ce1ffff29b" /># Employee Attendance Management System

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

3.5 User Interface Design
3.4.1 Login Interface 

<img width="868" height="539" alt="image" src="https://github.com/user-attachments/assets/7dc7edf9-9ede-4fdd-8ad5-922eba2c0b8e" />
Figure 16 : Login Page

<img width="487" height="571" alt="image" src="https://github.com/user-attachments/assets/6462fda4-80a1-42f3-bbb4-f6390874bbd2" />
Figure 17 : Register User Page

3.4.1.1 Profile Module

<img width="606" height="343" alt="image" src="https://github.com/user-attachments/assets/435f6235-527b-4056-b10e-36f6f7d26f04" />
Figure 18 :  HRD Dashboard

<img width="606" height="303" alt="image" src="https://github.com/user-attachments/assets/f07bc718-6503-40b0-a4b6-f40bcd2c56e0" />
Figure 19 :  HRD Profile Update

<img width="605" height="341" alt="image" src="https://github.com/user-attachments/assets/7fc7b911-d267-419c-95a1-3eb493511162" />
Figure 20 :  HRD Manage User Profile


<img width="606" height="300" alt="image" src="https://github.com/user-attachments/assets/901e1ff0-be81-48f8-b1d6-d36f7b14c0b2" />
Figure 21 :  PTJ Dashboard

<img width="607" height="298" alt="image" src="https://github.com/user-attachments/assets/0e44c519-1b86-440a-93ac-8d68ffc0651c" />
Figure 22:  Head Of PTJ Profile Update

<img width="603" height="341" alt="image" src="https://github.com/user-attachments/assets/3f6eca75-b64b-446a-9cf1-e2fca078151e" />
Figure 23 :  Academician Dashboard

<img width="597" height="336" alt="image" src="https://github.com/user-attachments/assets/1e2fd490-8f5f-47b3-8999-9055b6011eb9" />
Figure 24 : Academician Profile Update

<img width="590" height="338" alt="image" src="https://github.com/user-attachments/assets/b0fa9b30-6a1f-455b-bc77-6493c72cbaf2" />
Figure 25 :  Supporting Staff Dashboard

<img width="584" height="326" alt="image" src="https://github.com/user-attachments/assets/0382f15d-8491-40d0-bb8d-19fec57c8dc1" />
Figure 26 :  Supporting Staff Profile Update

3.4.2 Attendance Module

<img width="607" height="300" alt="image" src="https://github.com/user-attachments/assets/bc1fab63-a265-492b-b766-b7f60075cc19" />
Figure 27:  Academician Clock In/Out Attendance

<img width="579" height="327" alt="image" src="https://github.com/user-attachments/assets/e9aa6f93-582a-4d37-8a4b-f28971963e3d" />
Figure 28:  Supporting Staff Clock In/Out Attendance

<img width="591" height="330" alt="image" src="https://github.com/user-attachments/assets/73c73eb3-9d51-4c95-b26e-358844559f2c" />
Figure 29 :  Supporting Staff Clock In/Out Attendance History

<img width="582" height="330" alt="image" src="https://github.com/user-attachments/assets/c051947e-1d16-4456-b4cc-6368f28fdc74" />
Figure 30 :  HRD Approval Attendance

<img width="571" height="326" alt="image" src="https://github.com/user-attachments/assets/ae05a4f7-465b-4118-a135-88ad005c7a05" />
Figure 31 :  PTJ View Attendance Record

3.4.3 Overtime Module

<img width="583" height="332" alt="image" src="https://github.com/user-attachments/assets/f9912316-49a6-4e3a-acf6-31e1f3bcc21d" />
Figure 32 :  Supporting Staff Overtime Request Form

<img width="566" height="319" alt="image" src="https://github.com/user-attachments/assets/7f6e7c71-62e0-45a4-8628-ebe3e1ad6ab9" />
Figure 33 :  Head Of PTJ Overtime Request Lists 

<img width="560" height="317" alt="image" src="https://github.com/user-attachments/assets/7ef0928b-05ba-4545-bc4f-5cd6d2435edb" />
Figure 34 :  Head Of PTJ Overtime Request Approval

3.4.4 Leave Application Module

<img width="589" height="323" alt="image" src="https://github.com/user-attachments/assets/e0f52a82-4073-4515-8b1c-8496abc10547" />
Figure 35 :  Academician Leave Application Form


<img width="592" height="326" alt="image" src="https://github.com/user-attachments/assets/9191d6fd-1d35-4435-880c-8db8ec1df976" />
Figure 36:  Supporting Staff Leave Application Lists

<img width="600" height="299" alt="image" src="https://github.com/user-attachments/assets/8c833d77-6975-47cf-a700-90e35c96e5c6" />
Figure 37 :  Head Of PTJ Leave Application Approval
3.4.4 Create Report Module

<img width="608" height="345" alt="image" src="https://github.com/user-attachments/assets/5cf6654b-908c-4e4f-8003-4d602e3c9b7e" />
Figure 38 :  HRD Monthly Report Generate 

<img width="607" height="344" alt="image" src="https://github.com/user-attachments/assets/95bd25b6-d8c1-4dbc-9cf5-ddf828d00561" />
Figure 39:  HRD Monthly Report Generate 

---

## ⚠️ Notes

* This project was developed as part of coursework
* Some improvements (e.g., optimization, error handling) can be further enhanced
