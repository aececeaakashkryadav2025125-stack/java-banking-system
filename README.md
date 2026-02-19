# 💳 Java Banking System
A structured banking system built using layered architecture and file-based persistence to simulate real-world backend logic.

A console-based Banking Application developed using Core Java, designed with layered architecture and file-based persistence.

This project demonstrates strong understanding of Object-Oriented Programming (OOP), separation of concerns, and clean project structure.

---

## 🚀 Features

- Create Customer Account
- Deposit Money
- Withdraw Money
- Check Account Balance
- Transaction Recording
- File-Based Data Storage (Persistent Data)
- Layered Architecture Design

---

## 🏗 Architecture Overview

The application follows a structured layered design:

### 1️⃣ Domain Layer
Contains core business entities such as:
- Customer
- Account
- Transaction

### 2️⃣ Repository Layer
Responsible for data management and file handling:
- AccountRepository
- CustomerRepository
- TransactionRepository

Handles reading and writing data to files for persistence.

### 3️⃣ Service Layer
Contains business logic:
- BankService (Interface)
- BankServiceImpl (Implementation)

Ensures proper abstraction and loose coupling.

### 4️⃣ Application Layer
- Main.java handles user interaction and program execution.

---

## 💾 Data Persistence

This project uses **file-based storage** to:

- Save account data
- Load data at application startup
- Maintain transaction history
- Ensure data consistency

This simulates real-world persistence without using a database.

---

## 🛠 Technologies Used

- Java (Core Java)
- Object-Oriented Programming
- File I/O (FileReader, FileWriter / BufferedReader / Object Streams)
- IntelliJ IDEA
- Git & GitHub

---

## 📂 Project Structure
src/
├── domain/
├── repository/
├── service/
│ └── impl/
└── Main.java


---

## 🎯 Concepts Demonstrated

- Abstraction
- Encapsulation
- Interface-Based Design
- Layered Architecture
- Separation of Concerns
- File Handling
- Clean Code Practices

---
## 📌 Project Purpose

This project was developed to strengthen understanding of backend architecture design, file handling, and object-oriented programming principles in Java.



