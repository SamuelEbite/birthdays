# birthdays
CS50 Birthdays Project
Flask Birthday Tracker

This is a simple web application built with Flask that allows users to track birthdays. It stores the data in a SQLite database and provides a user interface for adding new entries and viewing existing ones.

Requirements

Python 3.x
Flask
CS50 Library
SQLite
Installation

Clone this repository to your local machine.
Install the required dependencies by running pip install -r requirements.txt in the project directory.
Create a new SQLite database file by running sqlite3 birthdays.db in the project directory.
Create the birthdays table by running the following command in the SQLite console:
sql
Copy code
CREATE TABLE birthdays (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    month INTEGER NOT NULL,
    day INTEGER NOT NULL
);
Exit the SQLite console by running .exit.
Start the application by running flask run in the project directory.
Open your web browser and go to http://localhost:5000 to use the application.
Usage

The homepage of the application displays a form for adding a new entry to the database and a table of existing entries. To add a new entry, simply fill out the form with the person's name and birthdate and click the "Add" button. The new entry will be added to the database and displayed in the table. To view the entries in the database, simply refresh the page.

Credits

This application was built using Flask, a micro web framework for Python, and the CS50 Library, a Python module for working with SQL databases. licensed under the MIT License
