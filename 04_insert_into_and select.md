### INSERT INTO ###

Syntax: 

```
INSERT INTO table_name (column_1, column_2, column_3) VALES (value_1, value_2, value_3);

test=# INSERT INTO users (name, age, birthday) VALUES ('Rob', 46, '1930-01-25');
INSERT 0 1

```
### SELECT ###

```
test=# SELECT name, age, birthday FROM users;
 name | age |  birthday
------+-----+------------
 Rob  |  46 | 1930-01-25
(1 row)


test=# SELECT * FROM users;
 name | age |  birthday
------+-----+------------
 Rob  |  46 | 1930-01-25
(1 row)
```

