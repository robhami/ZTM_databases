### CREATE TABLE ###

Syntax:
```

CREATE TABLE table_name (column1 datatype, column_2 datatype, column_3 datatype);

test=# CREATE TABLE users (name text, age smallint, birthday date);
CREATE TABLE
test=#

```
to  call database: 
```

test=# \d
         List of relations
 Schema |  Name  | Type  |  Owner
--------+--------+-------+----------
 public | users  | table | postgres
 public | users2 | table | postgres
(2 rows)

```
to exit:
```
test=# \q
