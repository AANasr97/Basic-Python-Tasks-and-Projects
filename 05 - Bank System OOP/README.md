# Bank Account Management System

This project is a simple Bank Account Management System developed using Python. The system allows users to create a new account or access an existing one, deposit and withdraw money, and view their account balance. The program also allows banks to provide loans to users, with the option to specify loan amount and duration.

## How to use

To use this program, simply download or clone the repository and run the `bank_system.py` file in your preferred Python environment. Upon running the program, you will be prompted to create a new account or access an existing one. Once you have logged in, you can choose to deposit or withdraw money from your account, view your account balance, or apply for a loan (if supported by your bank).

## Code overview

The main program is contained in the `bank_system.py` file. The code defines two classes: `User` and `Bank`. The `User` class contains basic personal details of the user, while the `Bank` class inherits from `User` and adds functionality for bank-specific operations, such as deposit, withdrawal, and loan application. The `Bank` class also includes functions to read and write account information to a text file. The program also includes two child classes of `Bank`, `CIB` and `QNB`, which have their own loan application functions.

## Dependencies

This project requires Python 3.x and the ability to run Python scripts in your preferred environment.