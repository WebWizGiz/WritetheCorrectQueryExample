Exercise 1: Creating Tables
Create a table named `Courses` that stores information about the various courses offered by the Java Programming Institute. The table should have the following columns:
- `CourseID` (int)
- `CourseName` (varchar(255))
- `Instructor` (varchar(255))
- `Duration` (varchar(50))
- `City` (varchar(255))

 Exercise 2: Inserting Data
Insert the following records into the `Courses` table:
1. Java Basics, John Doe, 4 weeks, New York
2. Advanced Java, Jane Smith, 8 weeks, Los Angeles
3. Java Web Development, Mike Brown, 6 weeks, Chicago
4. Java for Mobile, Anna Johnson, 5 weeks, San Francisco

 Exercise 3: Selecting Data
Write a SQL query to select all courses that are offered in 'Los Angeles'.

 Exercise 4: Distinct Cities
Write a SQL query to find out the distinct cities where the courses are offered.

 Exercise 5: Ordering Records
Write two SQL queries to select all courses from the `Courses` table ordered by `CourseID` in ascending and then in descending order.

 Exercise 6: Filtering and Ordering
Assuming there was a typo in the city name for the 'Java for Mobile' course and it was entered as 'San Francicso', write a SQL query to select all courses offered in 'San Francisco', correcting the typo in the output without updating the table. Order the results by `CourseName`.

 Exercise 7: Inserting Multiple Records
Add two more courses to the `Courses` table with a single INSERT statement:
- Java Security, Sam Wilson, 7 weeks, Boston
- Java Performance Tuning, Carol Danvers, 9 weeks, Seattle

  Exercise 8: Complex Conditions
Write a SQL query to select all courses that are either 5 or 6 weeks long and are offered in cities starting with 'New' or 'San'.

  Exercise 9: Handling NULL Values
Assume some courses do not have an assigned instructor yet. Write two SQL queries: one to select all courses where the `Instructor` is `NULL` and another where the `Instructor` is not `NULL`.

  Exercise 10: Updating Records
The city for the 'Java Web Development' course has been changed from 'Chicago' to 'Boston'. Write a SQL query to update this record in the `Courses` table.

  Exercise 11: Deleting Records
A course named 'Java Basics' is no longer offered. Write a SQL query to delete this course from the `Courses` table.
