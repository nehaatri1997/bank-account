# bank-account

This Python script, bank_account.py, provides a simple simulation of a bank account system, with features to create an account, deposit money, withdraw funds, and check the account balance. The program is designed to demonstrate fundamental principles of object-oriented programming, including encapsulation and method-based actions on class instances.

# Features
Account Creation: Initialize a bank account with an initial balance.
Deposit Function: Add funds to the account.
Withdraw Function: Deduct funds from the account, with a balance check to prevent overdrafts.
Balance Inquiry: Display the current balance of the account.

# Getting Started
1. Prerequisites
Ensure you have Python 3 installed on your system.

2. Running the Script
To run the script, use the following command in the terminal:

python bank_account.py
Example Usage
1. Initialize an Account: Creates an account with an initial balance.
2. Deposit: Add money to the account and see the updated balance.
3. Withdraw: Withdraw money with a check on sufficient balance.
4. Check Balance: Print the current account balance.

# Code Overview
The code is structured around a BankAccount class, with the following main methods:

1. __init__: Initializes the account with an optional starting balance.
2. deposit: Adds a specified amount to the account balance.
3. withdraw: Deducts a specified amount from the balance, with an error if the balance is insufficient.
4. check_balance: Returns the current balance.
   
# Sample Code Snippet

# Create an account with an initial balance of 100
account = BankAccount(100)

# Deposit 50
account.deposit(50)

# Withdraw 30
account.withdraw(30)

# Check balance
print("Current Balance:", account.check_balance())

# Potential Enhancements
1. Error Handling: Implement custom exceptions for overdrafts or invalid inputs.
2. Transaction History: Track deposits and withdrawals for transaction history.
