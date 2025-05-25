💰 Expense Tracker – Python + MongoDB This is a desktop-based Expense Tracker application built using Python (Tkinter) for the GUI and MongoDB for backend data storage. It helps users manage their income, expenses, savings, and financial goals, and also allows them to export PDF reports.

🚀 Technologies Used Python (Tkinter for GUI)

MongoDB (NoSQL database)

Matplotlib (for graphs)

FPDF (to export reports as PDFs)

✨ Features 🧾 User Authentication – Register and login functionality

💸 Add & View Expenses – Categorized entries with date & description

💰 Add & View Income – Source and amount based income tracking

🎯 Set Goals – Monthly and yearly financial goal tracking

💾 Savings Tracker – Keep records of saved amounts with titles

📊 Visual Graphs – View income vs expense charts

📄 Export to PDF – Monthly report generation as a PDF

❌ Delete Entries – Remove incorrect or unwanted income/expense data

🛠️ How to Run Install Python packages (create a virtual environment if needed):

pip install pymongo fpdf matplotlib Start MongoDB on your system (make sure it runs on localhost:27017).

Run the application:

Edit python expense.py
 🧠 Project Structure .
 ├── expense.py # GUI frontend using Tkinter 
├── expense_backend.py # Backend logic for database and PDF handling 
└── requirements.txt # (Optional) for pip install 
📦 Optional: requirements.txt pymongo fpdf matplotlib
