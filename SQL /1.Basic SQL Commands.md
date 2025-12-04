

# 🟦 **Basic SQL Commands**

---

## **1) SELECT**

**Meaning:**
“Show me this data from that table.”

**Explanation:**

* SELECT is used to choose *which columns* you want to see.
* It does **not** modify data.
* It simply returns rows that match your conditions (if any).

**Example:**

```sql
SELECT name, age FROM users;
```

This means:

➡️ Look inside the `users` table and show me only the `name` and `age` columns of all rows.

---

## **2) INSERT INTO**

**Meaning:**
“Add a new row into the table.”

**Explanation:**

* INSERT creates new records.
* You provide column names and values.
* A new row is added to the table.

**Example:**

```sql
INSERT INTO users (name, age) VALUES ('Sahil', 22);
```

This means:

➡️ Create a brand-new row in `users` where `name = Sahil` and `age = 22`.

---

## **3) UPDATE**

**Meaning:**
“Change existing values inside the table.”

**Explanation:**

* UPDATE modifies one or more rows.
* Without a **WHERE**, *all rows* will be updated.
* Always update specific rows.

**Example:**

```sql
UPDATE users SET age = 23 WHERE name = 'Sahil';
```

This means:

➡️ Find the row where the user’s name is *Sahil* and set his age to *23*.

---

## **4) DELETE**

**Meaning:**
“Remove unwanted rows from the table.”

**Explanation:**

* DELETE permanently removes data.
* Structure stays the same.
* Use **WHERE** to avoid deleting everything.

**Example:**

```sql
DELETE FROM users WHERE age < 18;
```

This means:

➡️ Delete all rows from `users` where age is less than 18.

---



**"Continue Filtering Data"**
