# Finance-Tracker
Personal Finance Tracker
A command-line Personal Finance Tracker to record income and expenses, view transaction summaries, and visualize financial trends. This tool uses Python, Pandas, and Matplotlib with persistent CSV storage for quick and efficient money management.

Features
Add Transactions easily: record date, amount, category (Income/Expense), and description.

Summarize Finances: See totals for income, expenses, and net savings within any chosen date range.

View Transaction History: Display transactions filtered by date with clear formatting.

Visualize Trends: Plot daily income and expense curves to spot patterns using Matplotlib.

CSV Data Storage: All data is saved in finance_data.csv for portability and security.

Getting Started
Prerequisites

Python 3.x

Install required libraries:

bash
pip install pandas matplotlib
Running the Application

bash
python main.py
Follow on-screen instructions:

Add new transactions.

View transaction history and summary for any date range.

Optional: plot graphs of income and expense trends.

File Overview
File	Purpose
main.py	Main interface and logic for viewing and plotting
data_entry.py	Input validation and user prompts
finance_data.csv	Stores all transaction data (created automatically)
Example CSV Entries
date	amount	category	description
01-07-2024	1000	Income	Salary
02-07-2024	50	Expense	Groceries
How to Extend
Add new categories or enhance input fields in data_entry.py.

Expand data analysis or visualization in main.py.

License
Released under the MIT License.

Start managing your money smarter with this simple, robust tracker!
