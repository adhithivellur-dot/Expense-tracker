# EXPENSE TRACKER
A desktop application built with Python and Tkinter for tracking personal expenses with a user-friendly graphical interface.
## Overview
This Expense Tracker is a comprehensive desktop application that allows users to efficiently manage and monitor their daily expenses. The application provides an intuitive interface for adding, viewing, editing, and deleting expense records, with all data stored locally in an SQLite database. Users can track payment details including date, spender, description, amount, and payment method.

## Features
Add Expenses: Record new expenses with date, spender name, description, amount, and payment mode  

View Expenses: Display all expenses in a sortable table view  

Edit Expenses: Modify existing expense records  

Delete Expenses: Remove individual expenses or clear all records

Expense Details: View detailed information about selected expenses

Convert to Words: Preview expense entries in sentence format before adding

Multiple Payment Methods: Support for Cash, Cheque, Credit Card, Debit Card, and UPI

Date Picker: Easy date selection with calendar widget

Data Persistence: All data stored in SQLite database for reliable storage

## Technologies/Tools Used
Python 3.x: Core programming language

Tkinter: GUI framework for the desktop interface

SQLite3: Lightweight database for data storage

tkcalendar: Calendar widget for date selection

datetime: Date and time handling
 ## Installation
1.Clone the repository:
bashgit clone https://github.com/yourusername/expense-tracker.git
cd expense-tracker

2.Install required dependencies:
bashpip install tkcalendar

3.Run the application:
bashpython expense_tracker.py
The application will automatically create an SQLite database file (Expense Tracker.db) in the same directory on first run.


## Instructions for Testing
### Adding an Expense
Fill in all fields in the left data entry panel:

1.Select a date using the date picker
   
2.Enter the description of the expense

3.Enter the amount

4.Enter the spender name

5.Select the payment mode from the dropdown

6.Click "Add expense" button

7.Verify the expense appears in the table

### Editing an Expense
1.Select an expense from the table by clicking on it

2.Click "Edit Selected Expense" button

3.Modify the fields as needed

4.Click the "Edit expense" button that appears

5.Confirm the changes are reflected in the table

### Deleting an Expense
1.Select an expense from the table

2.Click "Delete Expense" button

3.Confirm the deletion in the popup dialog

4.Verify the expense is removed from the table

### Viewing Expense Details
1.Select an expense from the table

2.Click "View Selected Expenses" button

3.Check that the fields populate with the selected expense data

### Converting to Words
1.Fill in all expense fields

2.Click "Convert to words before adding" button

3.Review the expense in sentence format

4.Choose to add or cancel

## Result
<img width="1912" height="972" alt="Screenshot 2025-11-23 165652" src="https://github.com/user-attachments/assets/fd82f193-361d-41a8-a973-e54d808a39ce" />
