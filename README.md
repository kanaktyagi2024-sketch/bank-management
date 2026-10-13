# 🏦 Bank Account Management System

A simple Bank Account Management System built using **JavaScript** and **Object-Oriented Programming (OOP)** concepts. This project demonstrates how bank accounts can be created and managed using classes, objects, inheritance, encapsulation, and method overriding.

## ✨ Features

- 🧑 Create a bank account with an account holder's name and balance.
- 💰 Check the current account balance.
- ➕ Deposit money into an account.
- ➖ Withdraw money from an account.
- ⚠️ Display a message for invalid deposits and insufficient balance.
- 🏦 Create a savings bank account with an interest rate.
- 🔒 Keep the account balance private using JavaScript private fields.
- 🔄 Override methods to display different account types.

## 🛠️ Technologies Used

- **JavaScript (ES6+)** – Implements the account functionality.
- **Object-Oriented Programming (OOP)** – Organizes the code using classes and objects.

## 📚 OOP Concepts Used

### 1. Class and Object

The `BankAccount` class defines the properties and methods of a bank account. Objects such as `sarvendraSBI` and `manishSBI` represent individual accounts.

### 2. Encapsulation

The `#balance` field is private, so it cannot be accessed directly from outside the class.

### 3. Inheritance

The `SavingBankAccount` class inherits properties and methods from the `BankAccount` class using `extends`.

### 4. Method Overriding

The `getAccountType()` method is redefined in `SavingBankAccount` to display a different account type.

### 5. Constructor and `super()`

The constructor initializes account details, while `super()` calls the parent class constructor.

## 📂 Project Structure

```text
Bank-Account-Management/
│
├── index.js
└── README.md
```

*Note: Replace `index.js` with your actual JavaScript filename if it is different.*

## 🚀 How to Run the Project

1. Install [Node.js](https://nodejs.org/) if it is not already installed.

2. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

3. Open the project folder in your terminal.

4. Run the JavaScript file:

   ```bash
   node index.js
   ```

5. View the output in the terminal.

## 💻 Example Operations

The project demonstrates the following operations:

- Create a bank account with an initial balance of ₹5,000.
- Deposit ₹2,000.
- Withdraw ₹1,000.
- Create a savings account with an initial balance of ₹12,000 and an interest rate of 8%.
- Display account details and account types.

## 🎯 Project Objective

The objective of this project is to understand and practice JavaScript OOP concepts through a real-world banking example.

## 🔮 Future Improvements

- Calculate and add interest to savings accounts.
- Prevent negative withdrawal amounts.
- Add account numbers and transaction history.
- Create a user interface using HTML and CSS.

## 👨‍💻 Author

**kanak tyagi**

