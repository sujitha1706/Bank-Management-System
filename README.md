# 🏦 Bank Management System

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/JDBC-007396?style=flat&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat"/>
</p>

A Java-based console application simulating a complete bank management system with account operations, transaction management, and an admin panel.

---

## 📌 Problem Statement

Manual banking operations are time-consuming and error-prone. This system automates core banking tasks — account creation, deposits, withdrawals, and transaction tracking — using Java and MySQL, making it efficient and reliable.

---

## ✨ Features

### 👤 User Module
- ✅ User registration and secure login
- ✅ Create new bank accounts with auto-generated Account Number & PIN
- ✅ Deposit and withdraw money
- ✅ Check account balance
- ✅ View complete transaction history

### 🔐 Admin Module
- ✅ View and manage all user accounts
- ✅ Monitor transactions across all accounts
- ✅ Maintain and secure the system

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Java |
| Database | MySQL |
| DB Connectivity | JDBC |
| IDE | IntelliJ IDEA / Eclipse |

---

## 📁 Project Structure

```
Bank-Management-System/
├── src/
│   ├── AccountCreation.java
│   ├── Deposit.java
│   ├── Withdrawal.java
│   ├── BalanceEnquiry.java
│   ├── TransactionHistory.java
│   ├── Login.java
│   └── Main.java
├── .gitignore
└── README.md
```

---

## ⚙️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/sujitha1706/Bank-Management-System.git

# 2. Open in IntelliJ IDEA or Eclipse

# 3. Create MySQL database
CREATE DATABASE bankdb;

# 4. Update DB credentials in your JDBC connection file:
# URL: jdbc:mysql://localhost:3306/bankdb
# Username: your_mysql_username
# Password: your_mysql_password

# 5. Add MySQL JDBC Driver (Connector/J) to classpath

# 6. Run Main.java
```

---

## 📸 Sample Output

```
=== BANK MANAGEMENT SYSTEM ===
1. User Login
2. Admin Login
3. New User Registration
4. Exit
Enter choice: 1

Enter Account Number: 1001234567
Enter PIN: ****
Login Successful!

=== USER MENU ===
1. Deposit
2. Withdraw
3. Balance Enquiry
4. Transaction History
5. Logout
```

---

## 👩‍💻 Author

**Sujitha Aparna Pepakayala**
- GitHub: [@sujitha1706](https://github.com/sujitha1706)
- LinkedIn: [sujitha-aparna-pepakayala](https://www.linkedin.com/in/sujitha-aparna-pepakayala-74b4b4278)

---

## 📜 License

MIT License — free to use and modify.
