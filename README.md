User story 1:
In order to show a list of bookmarks, then I want a drop down of bookmarks.

![User story 1 map](img_20200309_150248.jpg)

To setup the database from scratch:
1. Connect to psql
2. Create the database using the psql command CREATE DATABASE bookmark_manager;
3. Connect to the database using the pqsl command \c bookmark_manager;
4. Run the query we have saved in the file 01_create_bookmarks_table.sql

To create the test database from scratch:
1. Connect to psql
2. Create the database using the psql command CREATE DATABASE bookmark_manager_test;
3. Create a table by CREATE TABLE bookmarks(id SERIAL PRIMARY KEY, url VARCHAR(60));
4. Run the query we have saved in the file 01_create_bookmarks_table.sql
