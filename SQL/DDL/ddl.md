Here is the **corrected SQL with proper Markdown formatting**, including **fixed syntax errors** and **proper MySQL commands**.

---

# ✅ **MySQL Commands in Markdown (Correct Syntax)**

````md
# 1. Create a new database

```sql
CREATE DATABASE my_database;
````

---

# 2. Create a table

```sql
CREATE TABLE departments (
    dept_id INT AUTO_INCREMENT PRIMARY KEY,
    dept_name VARCHAR(50) NOT NULL UNIQUE
);
```

---

# 3. ALTER TABLE Commands

## ➤ Add a new column

```sql
ALTER TABLE departments 
ADD year INT;
```

---

## ➤ Modify a column (correct syntax)

⚠ MySQL requires you to specify datatype when modifying.

```sql
ALTER TABLE departments 
MODIFY year INT NOT NULL;
```

---

## ➤ Drop a column (correct syntax)

```sql
ALTER TABLE departments 
DROP COLUMN year;
```

```

---

# ⭐ Notes  
✔ `AUTO_INCREMENT` (not AUTO INCREMENT)  
✔ `MODIFY` must include datatype  
✔ `DROP COLUMN` syntax corrected  
✔ Markdown format ready for GitHub  

---
```
