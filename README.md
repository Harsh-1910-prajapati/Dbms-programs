# 📦 DBMS Programs

A collection of **Database Management System (DBMS)** programs and SQL queries covering core concepts — from basic DDL/DML to advanced PL/SQL, stored procedures, triggers, and more.

---



---

## 📚 Topics Covered

### 1. DDL (Data Definition Language)
- `CREATE TABLE` — Define tables and constraints
- `ALTER TABLE` — Add/modify/drop columns
- `DROP TABLE` — Remove tables
- `TRUNCATE` — Remove all rows

### 2. DML (Data Manipulation Language)
- `INSERT INTO` — Add new records
- `UPDATE` — Modify existing records
- `DELETE FROM` — Remove specific records

### 3. DQL (Data Query Language)
- `SELECT` with `WHERE`, `ORDER BY`, `GROUP BY`, `HAVING`
- Aggregate functions: `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`
- Subqueries (Nested Queries)
- Set operations: `UNION`, `INTERSECT`, `MINUS`

### 4. Joins
- `INNER JOIN`
- `LEFT JOIN` / `RIGHT JOIN`
- `FULL OUTER JOIN`
- `SELF JOIN`
- `CROSS JOIN`

### 5. PL/SQL
- Anonymous blocks
- Stored Procedures
- Functions
- Exception Handling

### 6. Triggers
- `BEFORE INSERT` / `AFTER INSERT`
- `BEFORE UPDATE` / `AFTER UPDATE`
- `BEFORE DELETE` / `AFTER DELETE`
- Row-level and Statement-level triggers

### 7. Cursors
- Implicit Cursors
- Explicit Cursors
- Cursor `FOR` loop

### 8. DCL & TCL
- `GRANT` and `REVOKE` privileges
- `COMMIT`, `ROLLBACK`, `SAVEPOINT`

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Oracle SQL / MySQL | Database Engine |
| SQL*Plus / MySQL Workbench | Query Execution |
| PL/SQL | Procedural Extension |

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/Harsh-1910-prajapati/Dbms-programs.git
   cd Dbms-programs
   ```

2. **Open your SQL environment** (Oracle SQL*Plus, MySQL Workbench, or any SQL IDE)

3. **Run the `.sql` files**
   ```sql
   @path/to/filename.sql
   ```
   Or copy-paste the SQL code directly into your SQL editor.

---

## 📝 Sample Program

```sql
-- Example: Creating a Student Table
CREATE TABLE Student (
    StudentID   NUMBER PRIMARY KEY,
    Name        VARCHAR2(50) NOT NULL,
    Department  VARCHAR2(30),
    Marks       NUMBER(5, 2)
);

-- Insert sample records
INSERT INTO Student VALUES (1, 'Harsh Prajapati', 'Computer Science', 91.5);
INSERT INTO Student VALUES (2, 'Ravi Shah', 'Information Technology', 85.0);

-- Retrieve all students
SELECT * FROM Student ORDER BY Marks DESC;
```

---

## 👨‍💻 Author

**Harsh Prajapati**  
🔗 [GitHub Profile](https://github.com/Harsh-1910-prajapati)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> ⭐ If you found this helpful, consider giving the repository a star!
