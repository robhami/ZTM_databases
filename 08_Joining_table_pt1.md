
In GUI add the following and run:
```
CREATE TABLE login (
	ID serial NOT NULL PRIMARY KEY,
	secret VARCHAR (100) NOT NULL,
	name text UNIQUE NOT NULL
);
```

This does the following:

Create a table called login

Data type serial is auto incrementing integer value, every new user assign it increments. NOT NULL has to be filled in. 
PRIMARY KEY assigned, this is what to access when  looking for things, PRIMARY KEY is always unique for each row, normally only one per table.

secret is a VARCHAR (size) where size is the number of characters to store. Variable-length string. (i.e. will not begreater than 100). And is NOT NULL

name text has to be UNIQUE and NOT NULL

Then to add data do the folowing in GUI: 

```
INSERT INTO login (secret, name) VALUES ('abc','Rob');
```
This will add values to new table dont need ID because that's automatic. Can just change values to add other users.

![Alt Text](https://github.com/robhami/ZTM_databases/blob/master/login_table.PNG)

![Alt Text](https://github.com/robhami/ZTM_databases/blob/master/main_db.PNG)
