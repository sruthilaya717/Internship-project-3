Expense Tracker
A simple Python-based expense tracker that allows you to:

Add daily expenses
View all recorded expenses
View a monthly summary of expenses
View category-wise expenditure
Features
Add Expense: Record an expense with date, category, amount, and description.
View Expenses: Display all expenses sorted by date.
Monthly Summary: Calculate and display the total amount spent in a specified month.
Category-wise Expenditure: Display the total amount spent on a specific category.
Prerequisites
Python 3.x
How to Run
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/expense-tracker.git
Navigate to the project directory:
bash
Copy code
cd expense-tracker
Run the program:
bash
Copy code
python3 expense_tracker.py
Usage
Upon running the program, you will see the following menu:

pgsql
Copy code
Expense Tracker
1. Add Expense
2. View Expenses
3. View Monthly Summary
4. View Category-wise Expenditure
5. Exit
Choose an option by entering the corresponding number:

Add Expense: Input the date (YYYY-MM-DD), category, amount, and a brief description.
View Expenses: Lists all expenses by date.
View Monthly Summary: Enter the year and month to see total expenditure for that month.
View Category-wise Expenditure: Enter a category to see total spending in that category.
Exit: Closes the application.
Example
pgsql
Copy code
Expense Tracker
1. Add Expense
2. View Expenses
3. View Monthly Summary
4. View Category-wise Expenditure
5. Exit
Enter your choice: 1
Enter date (YYYY-MM-DD): 2025-02-15
Enter category: Food
Enter amount: 15.50
Enter description: Lunch at cafe
Expense added successfully!
Project Structure
bash
Copy code
expense-tracker/
│   expense_tracker.py    # Main script for the expense tracker
│   README.md             # Project documentation
Potential Improvements



