### 1. The total number of Users (i.e. count of all users) in the system.
### `SELECT COUNT(*) FROM teamrobert2021;`

### 2. The total number of Users in Accounting Department.
### `SELECT COUNT(*) FROM teamrobert2021 WHERE department='Accounting';`

### 3. The total number of Users that have not activated their account.
### `SELECT COUNT(*) FROM teamrobert2021 WHERE status='Pending';`

### 4. List the first 5 Users that registered for an account in the system.
### `SELECT * FROM teamrobert2021 LIMIT 5;`

### 5. All Users whose age is greater than 18 but less than 26.
### `SELECT * FROM teamrobert2021 WHERE age BETWEEN 19 AND 25;`

### 6. All Users that registered for an account last week Thursday.
### `SELECT * FROM teamrobert2021 WHERE createed_dt='2020-02-01';`

### 7. All Users that registered for an account between last week Saturday and this week Monday.
### `SELECT * FROM teamrobert2021 WHERE createed_dt BETWEEN '2020-04-01' AND '2020-06-01';`

### 8. Query to Activate all pending Users in the system.
### `UPDATE teamrobert2021 SET status='Activated';`

### 9. Query to Update the User whose name is Tim to Timothy.
### `UPDATE teamrobert2021 SET name='Timothy' WHERE name='Tim';`

### 10. Total Number of Users in each Department.
### `SELECT COUNT(*), department from teamrobert2021 GROUP BY department;                                                                         `
