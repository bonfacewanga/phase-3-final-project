<!-- # Library Management System
This is a Python-based library management system that helps users manage authors, publishers, and books through a command-line interface (CLI). 
The application utilizes SQLite for database operations and adheres to best practices in object-oriented programming.

## Prerequisites
Before you begin, make sure you have the following installed on your system:

Python 3.x
SQLite3
Pipenv

## Installation
Clone the Repository and navigate into it:
git clone https://github.com/bonfacewanga/phase-3-final-project

Install Dependencies:
pipenv install

Activate the Virtual Environment:
pipenv shell

Create the Database and Tables:
python main.py

# Usage
Adding Authors: 
   python main.py add_author "Author Name"

Listing Authors:
   python main.py list_authors

Adding Publishers:
   python main.py add_publisher "Publisher Name"

Listing Publishers:
   python main.py list_publishers

Adding Books:
   python main.py add_book "Book Title" "Copy Number"

Listing Books:
   python main.py list_books

Assigning Author to Book:
   python main.py assign_author <book_id> <author_id>

Assigning Publisher to Book:
   python main.py assign_publisher <book_id> <publisher_id>

# Project Deliverables

## CLI Application (cli.py):
Allows users to manage authors, publishers, and books through text-based commands.

## Database with 3+ Related Tables (database.py):
Implements tables for authors, publishers, and books with proper foreign key relationships.

## Object-Relational Mapping (ORM) with SQLAlchemy (cli.py):
Connects Python objects to database tables using SQLAlchemy ORM.

## Virtual Environment Management (Pipenv):
Ensures dependency isolation and project reproducibility.

## Data Structures and Algorithms (algorithm.py):
Demonstrates a sample doubling algorithm for input data.

## Proper Package Structure:
Organizes code into modules (cli.py, database.py, books.py, algorithm.py) adhering to best practices.

## Use of Lists, Dicts, and Tuples:
Utilizes these data structures for various data storage and manipulation tasks.

This project fulfills the specified requirements, showcasing proficiency in Python fundamentals, object-oriented programming, SQL, SQLAlchemy ORM, and CLI application development.


 -->
