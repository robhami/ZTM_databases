Start Postgres with user postgres, then create database called test. Add values in PGAdmin and call them in terminal. 
Had to set a path in windows to get psql to run in terminal- type env into search bar and add path tto Postres bin folder.
```
C:\Users\Rob.000>psql -U postgres
Password for user postgres:
psql (11.2)
WARNING: Console code page (437) differs from Windows code page (1252)
         8-bit characters might not work correctly. See psql reference
         page "Notes for Windows users" for details.
Type "help" for help.

postgres=# CREATE DATABASE test
postgres-# ;
CREATE DATABASE
postgres=# \c test
WARNING: Console code page (437) differs from Windows code page (1252)
         8-bit characters might not work correctly. See psql reference
         page "Notes for Windows users" for details.
You are now connected to database "test" as user "postgres".
test=# SELECT * FROM users;
 id | name | email
----+------+-------
(0 rows)
```
Added the below in PGadmin: 

```
test=# SELECT * FROM users;
 id | name |     email
----+------+----------------
  1 | John | john@gmail.com
(1 row)
