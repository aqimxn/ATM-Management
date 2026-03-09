# 🏦 ATM Management System

## 📌 Overview

The **ATM Management System** is a Java-based web application designed to simulate core banking operations of an Automated Teller Machine (ATM). The system allows users to perform essential banking transactions such as withdrawing money, depositing funds, checking account balances, and managing customer records.

The application is deployed using **Apache Netbeans** and uses **MySQL** for database management, demonstrating practical implementation of **Java GUI development, database integration, and transaction management**.

---

## 🎯 Objectives

* Simulate ATM banking operations in a secure environment.
* Implement customer account management using Java.
* Store and manage transaction data using a relational database.
* Provide a structured system for performing ATM transactions.

---

## ✨ Features

* 🔐 User authentication
* 💰 Balance inquiry
* 💸 Cash withdrawal
* 💳 Deposit money
* 📋 Transaction management
* 🗄️ MySQL database integration

---

## 🛠️ Tech Stack

### Backend

* Java
* JSP / Servlets

### Server

* Apache Tomcat 10

### Database

* MySQL

### Libraries

* MySQL Connector
* JCalendar
* JGoodies

### Tools

* Eclipse IDE
* Git
* GitHub

---

## 📂 Project Structure

```id="atm_struct"
ATM-Management/
│
├── tomcat/apache-tomcat-10.1.15/
│   ├── bin/
│   ├── conf/
│   ├── lib/
│   ├── logs/
│   ├── webapps/
│   │   └── ROOT/
│   └── work/
│
├── atmdb.sql                # Database schema
├── mysql_connector.jar
├── jcalendar-1.4.jar
├── jgoodies-common-1.2.0.jar
├── jgoodies-looks-2.4.1.jar
├── junit-4.6.jar
│
└── README.md
```

---

## ⚙️ System Workflow

1️⃣ User logs into the ATM system
2️⃣ System authenticates the user account
3️⃣ User selects a transaction option:

* Withdraw money
* Deposit funds
* Check balance

4️⃣ The system processes the request
5️⃣ Transaction details are stored in the database
6️⃣ Updated account information is displayed

---

## 🚀 Installation

### 1️⃣ Clone the repository

```id="atm_clone_cmd"
git clone https://github.com/aqimxn/ATM-Management.git
```

---

### 2️⃣ Setup Apache Tomcat

Download and install **Apache Tomcat 10**

Place the project inside:

```id="atm_webapps"
tomcat/webapps/
```

---

### 3️⃣ Setup the database

Create a MySQL database and import:

```id="atm_sql_import"
atmdb.sql
```

---

### 4️⃣ Configure database connection

Update the database credentials in your Java connection file:

```id="atm_db_config"
jdbc:mysql://localhost:3306/atmdb
```

---

### 5️⃣ Run the application

Start the Tomcat server and open:

```id="atm_url"
http://localhost:8080/
```

---

## 📊 Example Functions

| Feature             | Description               |
| ------------------- | ------------------------- |
| Login               | Authenticate ATM user     |
| Deposit             | Add funds to account      |
| Withdraw            | Withdraw money            |
| Balance Inquiry     | View account balance      |

---

## 🔒 Security Considerations

* User authentication
* Database transaction logging
* Input validation
* Secure database connection

---

## 🔮 Future Improvements

* Add **transaction history dashboard**
* Add **admin panel for account management**
* Deploy to **cloud-based server**

---

## 👨‍💻 Author

**Muhammad Aqiman**

GitHub: https://github.com/aqimxn