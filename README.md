# Bank-Application-Project
The Banking Application is a Python project that provides a simplified yet functional simulation of a banking system. With this application, users can perform a range of banking operations, including creating new accounts, securely logging in, depositing and withdrawing funds, resetting passwords, and checking account balances. It's designed to showcase essential concepts of database interaction and user authentication.

This project leverages Python and a MySQL database to manage user accounts and transactions. The application's features cover the entire user journey, from account creation to transaction processing and even password resets, enhancing its practicality and educational value.

To get started with the Banking Application, you'll need Python 3.x and a MySQL database, along with a few required Python libraries. The README provides clear installation instructions and usage guidance, ensuring users can quickly set up and explore the application's functionality.

# Banking Application

## Overview

The **Banking Application** is a Python project that simulates a basic banking system. This application allows users to create accounts, perform transactions, change passwords, and check their account balances. It's a simple yet functional system built to showcase fundamental database interaction and user authentication techniques.

## Features

- **User Signup**: New users can create accounts by providing their name, a secure password, and an initial deposit.
- **User Login**: Registered users can log in with their account number and password.
- **Credit and Debit Transactions**: Users can deposit or withdraw funds from their accounts securely.
- **Password Reset**: Users can reset their passwords by receiving a one-time password (OTP) via email.
- **Account Details**: Users can view their account details, including their account number and current balance.

## Prerequisites

- Python 3.x
- MySQL database
- Necessary Python libraries: `pymysql`, `getpass`, `smtplib`, and `math`

## Installation

1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed.
3. Set up a MySQL database and update the database connection details in the code.
4. Install the required Python libraries using `pip install pymysql`.

## Usage

1. Run the `banking_application.py` script to start the application.
2. Choose one of the following options:
   - **Signup**: Create a new account.
   - **Login**: Log in to an existing account.
   - **Forgot Password**: Reset your password with email verification.
   - **Exit**: Close the application.

