# Digital Library Record - II
# | Explanation & Understanding of Operators

To show existing table we created in previous unit from a database use the following command:

```sh
USE LibraryReport;
SELECT*FROM Book1;
```

### Output
```sh















```

Now we will see some examples of all 4 operators.

> NOTE: Add these examples in line number 3 after adding above 2 lines of codes. After gaining output from every example, remove line number 3 & add new example line at number 3 again & gain output.

## AND Operator Example

```sh
SELECT*FROM Book1 WHERE Author='Charles Dickens' AND Title='Oliver Twist';
```

### Output
```sh











```

## OR Operator Example

```sh
SELECT*FROM Book1 WHERE Author='Charles Dickens' OR Title='Malgudi Days';
```

### Output
```sh










```

## IN Operator Example

```sh
SELECT*FROM Book1 WHERE Book_ID IN ('201', '205');
```

### Output
```sh







```

## NOT IN Operator Example

```sh
SELECT*FROM Book1 WHERE Book_ID NOT IN ('201', '205');
```

### Output
```sh









```