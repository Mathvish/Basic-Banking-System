# Basic-Banking-System

This project is a basic console-based banking system implemented in Java. It allows users to create a bank account, deposit money, withdraw money, and check the current balance. This is a beginner-level project aimed at helping developers understand and practice core Java concepts such as classes, objects, methods, and basic I/O operations.

## Features

- **Create a Bank Account**: Automatically initializes with a balance of 0.
- **Deposit Money**: Allows users to deposit any positive amount into their account.
- **Withdraw Money**: Allows users to withdraw an amount from their account, provided they have sufficient funds.
- **Check Balance**: Displays the current balance in the account.
- **Exit**: Safely exits the application.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine.
- A Java IDE (e.g., IntelliJ IDEA, Eclipse, or NetBeans) or a text editor (e.g., VSCode) with Java support.

### Running the Application

1. **Clone or Download the Repository**: 
   - You can clone the repository using Git or download the source files directly.

2. **Compile and Run**:
   - If using a command line, navigate to the directory containing the `.java` files.
   - Compile the program using the command:
     ```bash
     javac BankingSystem.java
     ```
   - Run the compiled program using:
     ```bash
     java BankingSystem
     ```

3. **Interact with the Program**:
   - Follow the on-screen instructions to deposit, withdraw, check your balance, or exit the program.

## Code Overview

### `BankAccount` Class

- **Attributes**:
  - `private double balance`: Stores the current balance of the account.

- **Methods**:
  - `public BankAccount()`: Constructor that initializes the balance to 0.
  - `public void deposit(double amount)`: Adds a specified amount to the balance if the amount is positive.
  - `public void withdraw(double amount)`: Subtracts a specified amount from the balance if the amount is positive and less than or equal to the current balance.
  - `public double getBalance()`: Returns the current balance.

### `BankingSystem` Class

- The `BankingSystem` class contains the `main` method, which serves as the entry point of the application.
- It utilizes a `Scanner` object to capture user input and interact with the `BankAccount` class.
- The program runs in a loop, allowing the user to perform multiple transactions until they choose to exit.

## Example Usage

- **Deposit**: Enter the amount to deposit, e.g., `1000`.
- **Withdraw**: Enter the amount to withdraw, e.g., `500`.
- **Check Balance**: Displays the current balance.
- **Exit**: Ends the session.

## Potential Improvements

- **Transaction History**: Add a feature to track and display all transactions.
- **Multiple Accounts**: Extend the system to support multiple users/accounts.
- **Interest Calculation**: Implement interest calculation on savings.

## License

This project is open-source and free to use 


