# Database
- Creation of database in mysql inside Vagrant
  - CREATE DATABASE Db_name;
  - Use Db_name;

- A table for students, courses, and teachers is generated.
  - CREATE TABLE Tb_name (column1 datatype, column2 datatype, column3 datatype, .....);
  
- In each table, records are entered.
  - INSERT INTO Table_name VALUES (Value1, Value2, Value3, .....);

- Records from the each table are displayed.
  - SELECT * FROM Table_name;

- Replace the records in each table.
  - UPDATE Table_name
  - SET Column_name = Value (value = different from previous value)
  - WHERE Column_name = Value; (value = same old value but primary key is more prioritized)

- Remove records from the database.
  - DELETE FROM Table_name WHERE Column_name = value;
