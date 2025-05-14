## SQL Queries: Analyzing a Database Online

This project contains SQL queries to analyze sales data for an online store. 

## Database Schema

```sql
CREATE TABLE orders (
    id INTEGER PRIMARY KEY,
    customer TEXT,
    amount REAL,
    order_date DATE
);

INSERT INTO orders (customer, amount, order_date) VALUES
('Alice', 5000, '2024-03-01'),
('Bob', 8000, '2024-03-05'),
('Alice', 3000, '2024-03-15'),
('Charlie', 7000, '2024-02-20'),
('Alice', 10000, '2024-02-28'),
('Bob', 4000, '2024-02-10'),
('Charlie', 9000, '2024-03-22'),
('Alice', 2000, '2024-03-30');
```
### Script-1 
![Screenshot 2025-05-14 160503](https://github.com/user-attachments/assets/44c1a09c-247f-4f8e-835c-3b08c631d724)

### Script-2
![Screenshot 2025-05-14 160507](https://github.com/user-attachments/assets/25ade3bc-ebec-4dd1-8355-94840e9b6c2e)

### Script-3 
![Screenshot 2025-05-14 160509](https://github.com/user-attachments/assets/d336ffeb-d447-46dc-a496-10726f0d7c06)

