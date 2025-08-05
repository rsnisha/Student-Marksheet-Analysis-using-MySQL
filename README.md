# 🎓 Student Marksheet Analysis using MySQL

This project contains **10 SQL questions** based on a sample `MARKSHEET` table to help learners practice core SQL concepts such as `SELECT`, `WHERE`, `ORDER BY`, aggregate functions, and more.

---

## 📋 Table Structure

The table used in this project is named `MARKSHEET` and includes the following columns:

| Column     | Type         | Description                       |
|------------|--------------|-----------------------------------|
| ID         | INT          | Student ID (e.g., 1803001)        |
| NAME       | VARCHAR(50)  | Student's full name (in uppercase)|
| ADDRESS    | VARCHAR(50)  | One of: DHAKA, KHULNA, BARISHAL, RAJSHAHI |
| GENDER     | VARCHAR(10)  | MALE or FEMALE                    |
| MATH       | INT          | Marks in Mathematics              |
| PHYSICS    | INT          | Marks in Physics                  |
| CHEMISTRY  | INT          | Marks in Chemistry                |
| BIOLOGY    | INT          | Marks in Biology                  |

---

## 🛠️ Table Creation SQL

```sql
CREATE TABLE MARKSHEET (
  ID INT PRIMARY KEY,
  NAME VARCHAR(50),
  ADDRESS VARCHAR(50),
  GENDER VARCHAR(10),
  MATH INT,
  PHYSICS INT,
  CHEMISTRY INT,
  BIOLOGY INT
);

```
---

## 🧠 Practice Questions

1. **Show all student names and their math marks sorted by highest math score.**

2. **Find all students who are from _DHAKA_ and scored more than _80_ in _BIOLOGY_.**

3. **Show the total marks (sum of math, physics, chemistry, biology) for each student.**

4. **Find the student with the highest total marks.**

5. **Count how many students are from each address (DHAKA, KHULNA, BARISHAL, RAJSHAHI).**

6. **Find the average marks in physics for FEMALE students.**

7. **List all students whose total marks are below 250.**

8. **Display all students sorted by address and then by name alphabetically.**

9. **How many MALE and FEMALE students are there?**

10. **Show students who have scored at least 90 in all four subjects (MATH, PHYSICS, CHEMISTRY, BIOLOGY).**

---

## ▶️ How to Use

1. Clone this repository or download the `MARKSHEET.sql` files.
2. Import the table.
3. Use SQL engine like MySQL
4. Run each query and observe the result.


---

## 📬 Contact

Feel free to share feedback or suggest improvements. Pull requests are welcome!
- Combine conditions with AND/OR
- Understand real-world table structures
