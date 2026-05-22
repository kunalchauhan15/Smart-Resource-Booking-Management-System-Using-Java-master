# 📊 Smart Resource Booking & Management System (SRBMS)

## 📌 Project Overview
**SRBMS** is a layered, console-based Java application built using **Maven**. It efficiently manages the booking and allocation of shared resources (like rooms) and follows a clean architecture with `DTO`, `DAO`, `Service`, `UI`, `Util`, and `Exception` layers.

This project demonstrates Core Java concepts such as **Object-Oriented Programming (OOP)**, **Collections**, **Exception Handling**, **Custom Sorting**, **Java Time API**, and **JUnit 5 testing**, making it ideal for both learning and demonstration purposes.

---

## 🚀 Features
- 🔐 **User Authentication & Role Management**
  - Secure sign-up/sign-in system  
  - Role-based access: Admin, Resource Manager, and Regular User

- 🏢 **Resource & Booking Management**  
  - Add, edit, delete, and view resources  
  - Book resources for a time period  
  - Custom sorting of rooms/bookings (by date, duration, name, etc.)  

- ⚠️ **Conflict Detection & Exception Handling**  
  - Prevent double bookings  
  - Custom exceptions for invalid input, unavailable resources, and access violations

- 📊 **Reporting & Analytics**  
  - List all bookings  
  - View bookings by user or resource  
  - Statistics and sorting capabilities

---

### 📁 Project Structure
```pgsql

│
├── SRBMS/
│ ├── src/main/java/rms/ 
│ │ └── App.java
│ │ └── dto
│ │ └── dao
│ │ └── daoImp   #implementing classes of dao package
│ │ └── service
│ │ └── ui
│ │ └── util
│ │ └── exception
| |
│ ├── src/test/java/rms/ 
│ │ └── AppTest.java
│ │ └── daoImp
│ │ └── service
│ └── pom.xml
```

## 🧪 Testing

✅ Unit testing done using **JUnit 5**  
✅ Test cases written for **DAO** and **Service** layers  
✅ Tested using Eclipse and Jupyter plugins (for educational setup)

---

## 🧰 Technologies Used

- **Language:** Java (Core Java)
- **Build Tool:** Maven
- **Testing:** JUnit 5
- **IDE:** Eclipse / IntelliJ IDEA
- **Architecture:** Layered (DTO, DAO, Service, UI, Util, Exception)
- **Storage:** In-memory lists (can be extended to files/db)

---

## 📚 What You'll Learn

- ✅ Layered Architecture in Java
- ✅ Core OOP Concepts
- ✅ Role-based Access Control
- ✅ Booking System & Scheduling Logic
- ✅ Custom Exception Creation
- ✅ JUnit 5 Testing (Basic Unit Testing)
- ✅ Sorting using Comparator & Comparable
- ✅ Console-based Application Development

---

## 📸 Sample Output
![image](https://github.com/user-attachments/assets/bf3f92ba-cff4-4528-818d-479f1e698acc)

---

## 🛠 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/devanshsingh15/Smart-Resource-Booking-Management-System-Using-Java
   
2. Import the project into IntelliJ IDEA, Eclipse, or any Java IDE.

3. Compile and Run: Run the App.java file to start the application.

---

## 📌 User Roles Overview

Admin->	Full access: Manage users, resources, bookings, and reports
Manager->	Manage resources and booking approvals
User->	View and book available resources

---

## 📈 Future Enhancements (Optional)

⌛ File or DB-based persistence

🖥 GUI with JavaFX or Swing

📩 Email simulation for booking confirmation

📈 Data analytics and charts

---

## 📜 License
This project is open-source and free to use for educational purposes.

## 🙋‍♂️ Author
Devansh
kunalchauhan0205@gmail.com

