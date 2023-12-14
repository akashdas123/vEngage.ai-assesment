### vEngage.ai-assesment
backend code for python assesment

## Phone Book Management System
This is a simple phone book management system implemented in Python using CSV file handling and SQLite database for CRUD operations. The application includes a CSV reader for phone book records and an SQL-like parser for managing phone book entries in a SQLite database.

## Setup
Clone the Repository:
git clone https://github.com/yourusername/phone-book-management.git
cd phone-book-management


## Install Dependencies:
pip install prettytable <p>

pip install sqlite3


## Usage
Read Phone Book Records from CSV:

## Place your phone book records in a CSV file (e.g., phone_records1.csv).

Run the Application:

Execute the phone_book_manager.py script to read records from the CSV file, create a SQLite database (phone_books1.db), and perform CRUD operations.

View and Modify Records:

The application will display phone book records with options to select, insert, and delete entries.
Avoiding Duplicates:

The system checks for duplicate names before inserting records to avoid redundancy.

SQL-like Parser Commands

### SELECT:

SELECT * FROM phone_records: Display all records.
SELECT * FROM phone_records WHERE Name='Doe': Display records with the name 'Doe'.

### INSERT:

INSERT INTO phone_records: Manually insert a new record.

### DELETE:

DELETE FROM phone_records WHERE LOWER(Name)='john': Delete records with the name 'John'.
Notes
Ensure the CSV file (phone_records1.csv) is correctly formatted with headers: Name, Email, Phone1, Phone2.

The application uses a SQLite database (phone_books1.db) to store and manage phone book records.

The PrettyTable library is used for displaying tables in a user-friendly format.
