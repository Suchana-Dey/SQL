**🏥 21-Day SQL Challenge**

Welcome to my **21-Day SQL Challenge** repository!  
This project documents my daily SQL learning and hands-on practice using MySQL.  

---

**📅 Day 1 — Database Setup & Basic Queries**

**Database:** hospital  
**Tool Used:** MySQL  

**🧠 Concepts Covered**
- Creating and using a database  
- Selecting all columns from a table  
- Retrieving specific columns  
- Displaying limited rows with `LIMIT`  
- Listing unique values using `DISTINCT`

  **Questions**
  /*1. Retrieve all columns from the `patients` table.*/
  /*2. Select only the `patient_id`, `name`, and `age` columns from the `patients` table.*/
  /*3. Display the first 10 records from the `services_weekly` table.*/
  /* List all unique hospital services available in the hospital.*/ 

**💻 Queries Practiced**
```sql
CREATE DATABASE hospital;
USE hospital;

SELECT * FROM hospital.patients;
SELECT patient_id, name, age FROM hospital.patients;
SELECT * FROM hospital.services_weekly LIMIT 10;
SELECT DISTINCT(service) FROM hospital.patients;
