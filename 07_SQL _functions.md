### SQL functions ###

#### AVERAGE ####
```
test=# SELECT AVG(score) FROM users;
         avg
---------------------
 84.5000000000000000
(1 row)
```

#### SUM #####
```
test=# SELECT SUM(age) FROM users;
 sum
-----
 185
(1 row)
```
#### COUNT ####
```
test=# SELECT COUNT(name) FROM users;
 count
-------
     4
(1 row)
```

There are a few more functions that can be used.
