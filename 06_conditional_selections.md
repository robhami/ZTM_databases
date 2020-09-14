### Conditional selections ###

Need to match case when searching:

```

test=# SELECT * FROM users WHERE name LIKE 'A%';
 name | age |  birthday  | score
------+-----+------------+-------
 Amy  |  46 | 1937-01-25 |    88
(1 row)

```

### Order ###

```
test=# SELECT * FROM users ORDER BY score DESC;
 name  | age |  birthday  | score
-------+-----+------------+-------
 Sally |  44 | 1932-01-25 |   100
 John  |  49 | 1922-01-25 |   100
 Amy   |  46 | 1937-01-25 |    88
 Rob   |  46 | 1930-01-25 |    50
(4 rows)


test=# SELECT * FROM users ORDER BY score ASC;
 name  | age |  birthday  | score
-------+-----+------------+-------
 Rob   |  46 | 1930-01-25 |    50
 Amy   |  46 | 1937-01-25 |    88
 Sally |  44 | 1932-01-25 |   100
 John  |  49 | 1922-01-25 |   100
(4 rows)
```
