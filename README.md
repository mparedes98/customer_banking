Customer Banking System
Overview
This customer banking system allows users to calculate and track interest earned on savings and CD accounts. Users can enter their account information, and the application will calculate the interest earned and update the balances after a specified period.
Features

Create and manage savings accounts
Create and manage certificate of deposit (CD) accounts
Calculate interest earned based on:

Initial balance
Interest rate
Time period (in months)


Display updated account balances with earned interest

Project Structure
The project consists of the following files:

Account.py: Contains the Account class with methods to set balance and interest
savings_account.py: Contains the function to create a savings account and calculate interest
cd_account.py: Contains the function to create a CD account and calculate interest
customer_banking.py: Main application file that interacts with the user

How to Use

Run the customer_banking.py file:
python customer_banking.py

Follow the prompts to enter information for your savings account:

Initial balance
Interest rate (as a percentage)
Time period (in months)


The application will display the interest earned and updated balance for your savings account
Next, follow the prompts to enter information for your CD account:

Initial balance
Interest rate (as a percentage)
Time period (in months)


The application will display the interest earned and updated balance for your CD account

Technical Details
The application uses simple interest formula to calculate the interest earned:
Interest = Principal × Rate × Time
Where:

Principal is the initial balance
Rate is the annual interest rate (as a decimal)
Time is the period in months (converted to a fraction of a year)

Requirements

Python 3.6 or higher

Example Output
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
