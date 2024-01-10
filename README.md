# Mikoi_Assignment
# Simple Database
This is a simple Java program that implements a basic database system. It allows you to create tables and insert values into them. 
The program uses text files to store metadata and records.

## Usage
You can use the following commands:
- CREATE TABLE <table_name> (col1 <datatype>, col2 <datatype>,...) - Create a table with the specified columns and data types.
- INSERT INTO <table_name> VALUES (val1,val2,...) - Insert values into a table.
- EXIT or QUIT - Terminate the program. GoodBye!!!
  
## Technical Stack Used
  - JAVA 17
  
## Example Commands
Here are some example commands you can try:

- ### Create a table:
```
CREATE TABLE myTable (col1 INTEGER, col2 STRING)
```
  
- ### Insert values into a table:
```
INSERT INTO myTable VALUES (150, 'Hello Harsh')
```
  
- ### Terminate the program:
```
EXIT OR QUIT
```
  
## File Structure
The program uses two files:
metaData.txt: Stores the metadata of the tables created.<br>
<table_name>.txt: Stores the records inserted into each table.<br>
Make sure both files are present in the same directory as the Java source file.
