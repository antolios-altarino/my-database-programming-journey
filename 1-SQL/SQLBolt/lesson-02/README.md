# Lesson 2 — Queries with Constraints (Pt. 1)

## Summary

In this lesson, I learned how to filter rows using the `WHERE` clause and apply different conditions to retrieve only the data I need.

I learned how to use comparison operators such as `=`, `!=`, `<`, `<=`, `>`, and `>=`, as well as `BETWEEN`, `NOT BETWEEN`, and `IN` to create conditions.

### Exercise 2 — Tasks

* [x] Find the movie with a row id of 6

```sql
SELECT * FROM movies
WHERE id = 6;
```

* [x] Find the movies released in the years between 2000 and 2010

```sql
SELECT * FROM movies
WHERE year BETWEEN 2000 AND 2010;
```

* [x] Find the movies not released in the years between 2000 and 2010

```sql
SELECT * FROM movies
WHERE year NOT BETWEEN 2000 AND 2010;
```

* [x] Find the first 5 Pixar movies and their release year

```sql
SELECT title, year FROM movies
WHERE id BETWEEN 1 AND 5;
```
