# Customer Banking System

## Overview
This customer banking system allows users to calculate and track interest earned on savings and CD accounts. Users can enter account information, and the application will calculate interest earned and update balances after a specified time period.

## Features
- Create and manage savings accounts
- Create and manage certificate of deposit (CD) accounts
- Calculate interest earned based on initial balance, rate, and time
- Display updated account balances with earned interest

## Technical Implementation
The system uses object-oriented programming principles in Python:

- Account.py - Base class with methods for balance and interest management
- savings_account.py - Module for savings account functionality
- cd_account.py - Module for Certificate of Deposit account functionality
- customer_banking.py - Main interface with user interaction logic

## Usage Instructions
1. Run the main script:
python customer_banking.py
2. Follow the prompts to enter your savings account information:
- Initial balance
- Interest rate (in percentage)
- Time period (in months)
3. Review the calculated interest and updated balance for your savings account
4. Enter your CD account information:
- Initial balance
- Interest rate (in percentage)
- Time period (in months)
5. Review the calculated interest and updated balance for your CD account

## Interest Calculation
The system uses the following formula for simple interest calculation:
Interest = Principal × (Rate ÷ 100) × (Months ÷ 12)
Where:
- Principal is the initial balance
- Rate is the annual interest rate in percentage
- Months is the time period divided by 12 to convert to years

## Example
Enter details for the Savings Account:
Enter the initial balance: $5000
Enter the interest rate (in percentage): 2.5
Enter the number of months: 12
Savings Account Results:
Interest Earned: $125.00
Updated Balance: $5125.00
Enter details for the CD Account:
Enter the initial balance: $10000
Enter the interest rate (in percentage): 3.5
Enter the number of months: 24
CD Account Results:
Interest Earned: $700.00
Updated Balance: $10700.00

## Requirements
- Python 3.6 or higher

## Project Structure
customer_banking/
├── Account.py            # Account class definition
├── cd_account.py         # CD account functionality
├── savings_account.py    # Savings account functionality
├── customer_banking.py   # Main application logic
└── README.md             # Project documentation

## Author
- Madelin Paredes
Here are two ways to create your README.md file:
Option 1: Create directly on GitHub

Go to your repository on GitHub.com
Click the "Add file" button
Select "Create new file"
Name it "README.md"
Paste the content above
Commit the file directly on GitHub

Option 2: Create locally with a text editor

Open a text editor (TextEdit, Notepad, VS Code, etc.)
Paste the content above
Save the file as "README.md" in your project folder
Use GitHub Desktop to commit and push the file

## Author
- Madelin Paredes
""")

print("README.md file has been created successfully!")
