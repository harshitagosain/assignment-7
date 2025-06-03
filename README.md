 Module 12 (Tutedude)
This repository contains practical exercises and Python scripts for working with **PostgreSQL** and **Python** using the `psycopg2-binary` module, as part of **Tutedude's Module 12
Module Topics Covered
- Creating and deleting a PostgreSQL database using psql
- Creating tables and inserting data using SQL and Python
- Connecting PostgreSQL with Python (`psycopg2`)
- Performing CRUD operations (Create, Read, Update, Delete)

conn = psycopg2.connect(
    dbname="student_db",
    user="postgres",
    password="your_password",
    host="localhost",
    port="5432"
)
Make sure student_db is created in your PostgreSQL instance.
# create_table()
# insert_data("Charlie", 92)
# fetch_data()
# user_input()
# test_insert_and_fetch()
Connection Error?
Make sure PostgreSQL server is running and the database name, user, and password are correct.

thank you

