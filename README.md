#  C Donation Management System

This project is a **C-based donation management system** developed as part of early university coursework to practice **struct usage, dynamic memory allocation, and file handling** in C programming.

The system allows users to make donations in different categories and keeps track of both **public and anonymous donations**.

---

##  Project Objective

The main objective of this project is to design a console-based system that enables users to:

- Register in the system
- Donate in different categories
- Choose between public or anonymous donations
- Track total donation amounts by category and visibility

---

##  Project Scenario

The application simulates a simple donation platform:

- Users register with personal information.
- Users select a donation category such as food, clothing, money, or other.
- Donations can be made either **publicly** or **anonymously**.
- Monetary donations require selecting a country, and the amount is converted to the target country's currency.
- The system displays total public and anonymous donation amounts.

---

##  System Design

The project is implemented using multiple **structs**, each responsible for a specific role:

### 🔹 Person
- Stores user information such as name, surname, email, password, and ID.

### 🔹 Donation
- Stores donation details
- Tracks donation category and anonymity status

### 🔹 DonationSystem
- Manages a dynamically allocated array of donations
- Handles donation storage and tracking logic

---

##  Features

- User registration system
- Donation in multiple categories (food, clothing, money, others)
- Public and anonymous donation options
- Currency conversion for monetary donations
- Tracking total donation amounts
- File-based data storage

---

##  Technologies Used

- C
- Structs
- Dynamic memory allocation
- File handling
- Console-based application

---

##  Project Structure

The project includes:

- Struct definitions (`Person`, `Donation`, `DonationSystem`)
- Donation and user management logic
- File storage for users and donations
- Test and main execution files

The code is separated into `.c` and `.h` files to maintain clarity and modularity.

---

##  Learning Outcomes

Through this project, I gained experience in:

- Designing structured programs in C
- Working with structs and pointers
- Managing dynamic memory
- Implementing file-based data storage
- Building rule-based console applications

---

## 📚 Notes

This project represents my **early programming experience** and is preserved to demonstrate my foundational knowledge of C programming and software design principles.
