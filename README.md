# Digital Library Record - I SB 10 Table Code

### Instructions
Previously we have created a database named `LibraryReport` & created a table named `Student` in that database. Now we will use same database and will create another table named `Book1`.

### Code
```sh
USE LibraryReport;
CREATE TABLE Book1 (
    Book_ID INT,
    Title VARCHAR(40),
    Author VARCHAR(20),
    Book_Issue_Date DATE,
    Edition_Number INT,
    Student_ID VARCHAR(10),
    PRIMARY KEY(Book_ID)
);
SHOW TABLES;
SELECT*FROM Book1;
INSERT INTO Book1 VALUES ('112', 'A Tale of Two Cities', 'Charles Dickens', '2021-10-03', '1', 'S009');
INSERT INTO Book1 VALUES ('201', 'David Copperfield', 'Charles Dickens', '2022-10-03', '1', 'S001');
INSERT INTO Book1 VALUES ('205', 'Oliver Twist', 'Charles Dickens', '2021-01-03', '4', 'S011');
INSERT INTO Book1 VALUES ('102', 'Robinson Crusoe', 'Daniel Defoe', '2021-12-03', '3', 'S002');
INSERT INTO Book1 VALUES ('121', 'The Hobbit', 'J.R.R. Tolkien', '2021-11-23', '1', 'S008');
INSERT INTO Book1 VALUES ('109', 'Malgudi Days', 'R.K. Narayan', '2021-10-10', '4', 'S027');
INSERT INTO Book1 VALUES ('176', 'The Adventures of Sherlock Holmes', 'Conan Doyle', '2021-10-03', '2', 'S015');
INSERT INTO Book1 VALUES ('199', 'The Hound of the Baskervilles', 'Conan Doyle', '2021-11-13', '3', 'S025');
SELECT*FROM Book1;
```

Now go to last line `SELECT*FROM Book1;` & run query by pressing `Thunder Icon`. You will see the table in output.

Perform a search operation on the table by writing `SELECT` and `WHERE` clauses shown below. Search for Student_ID 'S001'.

```sh
SELECT*FROM Book1 WHERE Student_ID='S001';
```

Go to last line & run query. You will see the search operation result in output.
