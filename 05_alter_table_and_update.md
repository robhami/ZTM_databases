### ALTER ###

```
ALTER TABLE table_name ADD column datatype;

test=# ALTER TABLE users ADD score smallint;
ALTER TABLE
```

### UPDATE ###
```
test=# UPDATE table_name
test-# SET some_column = some_value
test-# WHERE some_column = some_value

test=# UPDATE users SET score = 50 WHERE name='Rob';
UPDATE 1

test=# UPDATE users SET score = 100 WHERE name='John' OR name='Sally';
UPDATE 2
```
