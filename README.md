# Datasets

## movies_dummy_dataset.sql.zip

Location - 

```sql
mysql> select count(*) from movies;
+----------+
| count(*) |
+----------+
|   277562 |
+----------+

mysql> select count(*) from movies_liked;
+----------+
| count(*) |
+----------+
|     8671 |
+----------+

mysql> desc movies;
+-----------+--------+----------------+
| Field     | Type   | Properties     |
+-----------+--------+----------------+
| id        | bigint |                |
| title     | text   | indexed stored |
| actor_ids | mva    |                |
+-----------+--------+----------------+

mysql> desc movies_liked;
+----------+--------+------------+
| Field    | Type   | Properties |
+----------+--------+------------+
| id       | bigint |            |
| movie_id | uint   |            |
| user_id  | uint   |            |
+----------+--------+------------+
```
