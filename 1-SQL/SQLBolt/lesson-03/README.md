# Lesson 3 — Queries with Constraints (Pt. 2)

## Summary

In this lesson, I learned how to use text-based conditions with the `WHERE` clause.

I learned how to use `LIKE` for pattern matching, `NOT LIKE` for excluding text patterns, and wildcards such as `%` and `_` to match characters within text. I also learned how to use `IN` and `NOT IN` with text values.

### Exercise 3 — Tasks

* [x] Find all the Toy Story movies

```sql
SELECT * FROM movies
WHERE title LIKE "%Toy%";

* [x] Find all the movies directed by John Lasseter

```sql
SELECT * FROM movies
WHERE director = "John Lasseter";
```

* [x] Find all the movies (and director) not directed by John Lasseter

```sql
SELECT * FROM movies
WHERE director != "John Lasseter";
```

* [x] Find all the WALL-* movies

```sql
SELECT * FROM movies
WHERE title LIKE "%WALL-%";
```
