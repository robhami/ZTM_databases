
### Relational databases (e.g. postgreSQL) ###

2 or more tables with columns and rows. Each row represents an entry and each column stores specific type of info (e.g. name, address or phone numbers).

Relation between tables and fields is called a schema, this must be clearly defined before info is added. 

Information is connected - username same in users table as tweets table. So the username in tweets table is the FOREIGN KEY of the username in the users table. 

Then form_user in following table will be foreign key of username.

Something that identifies each row in a table e.g. full name or ID is called the PRIMARY KEY. 

![Alt Text](https://github.com/robhami/ZTM_databases/blob/master/relational_DB.PNG)

All relational databases use SQL.

### Non relational database (or non SQL database)- e.g. MongoDB ###

Lets you create database without having to define schema first. We can define as we go. They all have adifferent way of doing things. They are more flexible. 

MongoDB is DOCUMENT ORIENTED. Data is stored as documents. Each user held as a document with all info in it. 

Uses langauge called MongoDB query language. 



