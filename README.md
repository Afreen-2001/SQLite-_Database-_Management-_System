SQLite Database Management System
📌 Project Overview

The SQLite Database Management System is a simple command-line application developed using Python and SQLite. It allows users to manage records by performing basic CRUD operations: Create, Read, Update, and Delete.

The application stores records in a local SQLite database, making it easy to add, view, modify, and delete information without requiring a separate database server.

✨ Features
Insert Record: Add a new record with name, age, gender, address, contact number, and email.
Fetch Records: Display all stored records.
Update Record: Modify a specific field of an existing record using its ID.
Delete Record: Remove a record using its ID.
Persistent Storage: Store data in a local SQLite database file.
Parameterized Queries: Use SQL placeholders to help prevent SQL injection.
Input Validation: Handle invalid numeric inputs and missing record IDs.
🛠️ Technologies Used
Programming Language: Python
Database: SQLite
Database Library: Python sqlite3 module
📂 Project Structure
SQLite-Database-Management/
│
├── main.py
├── Sqlitedatabasenew.db
└── README.md


Note: The database file is created automatically when the application runs for the first time. main.py is the suggested filename for the Python source code.

⚙️ Requirements
Python 3.x
SQLite support through Python's built-in sqlite3 module

No external Python packages are required.

🚀 Installation and Setup
1. Clone the Repository
git clone https://github.com/Afreen-2001/SQLite-_Database-_Management-_System.git


Replace your-username with your GitHub username and use your actual repository URL.

2. Navigate to the Project Directory
cd SQLite-Database-Management

3. Run the Application
python main.py


Depending on your system, you may need to use:

python3 main.py

💻 Usage

After running the program, a menu appears in the terminal:

--- Database Management System ---
1. Insert Record
2. Fetch Records
3. Update Record
4. Delete Record
5. Exit

Please Enter Your Operation:


Choose an option by entering the corresponding number.

1. Insert Record

Enter the requested details:

Name
Age
Gender
Address
Contact number
Email address

The record will be saved to the database.

2. Fetch Records

Displays all records currently stored in the database, including their unique IDs.

3. Update Record

Select the field you want to update, enter the record ID, and provide the new value.

Available fields:

Name
Age
Gender
Address
Contact
Mail
4. Delete Record

Enter the ID of the record you want to delete. The application removes the matching record if it exists.

5. Exit

Closes the application and the database connection.

🗄️ Database Schema

The application creates a table named datas with the following columns:

Column	Data Type	Description
id	INTEGER	Primary key for each record
name	TEXT	Person's name
age	INTEGER	Person's age
gender	TEXT	Person's gender
address	TEXT	Residential address
contact	TEXT	Contact number
mail	TEXT	Email address

The id column is automatically generated as an integer primary key.

📚 Concepts Demonstrated

This project demonstrates fundamental programming and database concepts:

Python classes and objects
Object-oriented programming
SQLite database connectivity
SQL CREATE TABLE statements
SQL INSERT, SELECT, UPDATE, and DELETE statements
Parameterized SQL queries
Exception handling
User input and command-line interaction
🔮 Future Enhancements

Possible improvements include:

Develop a graphical user interface using Tkinter.
Add record search functionality.
Improve email and contact number validation.
Add sorting and filtering options.
Export records to CSV or Excel.
Add authentication and user access controls.
🎯 Learning Outcome

This project provides practical experience in Python programming, relational databases, SQL queries, and CRUD operations. It is suitable for beginners learning database connectivity and building command-line applications.

📄 License

This project is available for educational and personal learning purposes. Add a specific open-source license, such as the MIT License, if you intend to distribute it under those terms.