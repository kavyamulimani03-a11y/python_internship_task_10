🏦 Bank Account Management System (Python OOP Project)
📌 Project Overview

This project is a simple Bank Account Management System built using Python.
It demonstrates core Object-Oriented Programming (OOP) concepts such as:

Classes and Constructors

Attributes and Methods

Encapsulation

Inheritance

Method Overriding

Multiple Object Creation

Real-world Banking Simulation

📂 File Structure
bank_account.py
README.md

🚀 Features
1️⃣ BankAccount Class

Create a bank account

Deposit money

Withdraw money

View account details

Encapsulated balance (private variable)

2️⃣ SavingsAccount Class (Inheritance)

Inherits from BankAccount

Adds interest calculation

Overrides withdraw method

Maintains minimum balance rule (₹500)

🧠 OOP Concepts Used
✅ Encapsulation

Balance is declared as private (__balance)

Accessed using a getter method (get_balance())

✅ Inheritance

SavingsAccount inherits from BankAccount

✅ Method Overriding

withdraw() method is overridden in SavingsAccount to enforce minimum balance

✅ Polymorphism

Same method name (withdraw) behaves differently depending on object type

▶️ How to Run the Program

Install Python (if not already installed)

Open terminal or command prompt

Navigate to the project folder

Run:

python bank_account.py

🏦 Example Operations Simulated

Creating multiple accounts

Depositing money

Withdrawing money

Checking minimum balance

Adding interest

Displaying account details

📌 Sample Output
500 deposited successfully.
300 withdrawn successfully.

--- Account Details ---
Account Holder: Kavya
Account Number: ACC1001
Balance: 1200

🎯 Learning Outcomes

After completing this project, you will understand:

How to design real-world systems using OOP

How inheritance improves code reusability

How encapsulation protects sensitive data

How method overriding customizes behavior

🔮 Future Improvements

Add current account type

Add transaction history

Store data in a file or database

Create menu-driven user interface

Add exception handling

👩‍💻 Author

Developed as part of Python OOP practice and learning.
