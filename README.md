# sqlDeliverable1

Ensure that you're in this lab's folder within the class repo.

Open VS Code: $ code .

Open a terminal session and run ls. Ensure that you see the three files: clues.sql, sql-lab.md & world.sql.

Start the psql interactive terminal: $ psql

Create a database named carmen and connect to it:

CREATE DATABASE carmen;
\c carmen
Create city, country & countrylanguage tables and seed their data using the import (\i) psql command:

\i world.sql
