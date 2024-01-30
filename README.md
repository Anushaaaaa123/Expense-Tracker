# Expense-Tracker
This program provides a simple interactive interface for users to add, view, and save expenses.
Working / Steps / Algorithm
1. Imported the json module for handling JSON data.
2. Used functions such as add_expenses, view_expenses, save_to_file and load_from_file.
   add_expenses :Takes the input from the user for a new expense and appends it to expense_items list.
   view_expenses : Shows tha details of all expenses in expense_list.
   save_to_file : Save the user input to a JSON file
   load_from_file : Reads the data in JSON file and returns it. 
3. Main program shows the menu options to the user.
4. If user doesn't enter anything it will show an error message.
5. When the user chooses the option 4, program will exit.
