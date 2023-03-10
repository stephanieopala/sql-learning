## Notes on SQL from the 30daysofSQL challenge
### Day 4
Data Types in SQL
- INT 
  - Refers to whole numbers
- DECIMAL(M,N) 
  - Refers to decimal numbers.
  - M refers to the total number of digits before the decimal point.
  - N refers to the total number of digits after the decimal point.
- VARCHAR(1)
  - Refers to a string 
  - The number in the paranthesis refers to the length of the characters in the string.
- BLOB
  - Stores a large amount of binary data e.g images/files.
- DATE
- TIMESTAMP

### Day 5
SQL Commands

- Create table with columns.
```sql
CREATE TABLE student (
student_id INT PRIMARY KEY,
name VARCHAR(20),
major VARCHAR(20)
);
```
- Describe the table that has been created.

```sql
DESCRIBE student;
```

- Delete a table
```sql
DROP TABLE student;
```

- Add a column to the table
```sql
ALTER TABLE student ADD gpa DECIMAL(3,2);
```

- Delete a column
```sql
ALTER TABLE student DROP COLUMN gpa;
```
