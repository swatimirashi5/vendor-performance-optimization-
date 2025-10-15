## Step 1 – Automated Data Ingestion

I built a Python script to automatically read **multiple vendor and inventory CSV files (5+ files, 10k+ rows each)** and load them into a **centralized SQLite database**.  
The script also logs which files were processed, how long it took, and any errors, ensuring the data is **reliable, organized, and ready for analysis**.  
This step creates a clean data foundation for the next stages of cleaning, transformation, and vendor performance evaluation.

### Tech Used
Python · Pandas · SQLAlchemy · SQLite · Logging  

### About SQLAlchemy
**SQLAlchemy** is a widely-used **Python library for interacting with relational databases**. In real-world companies, it serves as an **Object Relational Mapper (ORM)**, allowing developers to **write Python code to manage database records** without writing raw SQL queries.  

Benefits of using SQLAlchemy:  
- **Dynamic table management:** Automatically create or modify database tables based on data.  
- **Clean and maintainable code:** Interact with the database using Python objects instead of raw SQL.  
- **Production-ready reliability:** Efficiently manages database connections and transactions.  
- **Integration with other Python tools:** Works seamlessly with Pandas, SQLite, PostgreSQL, and MySQL.  

In this project, SQLAlchemy was used to **dynamically create database tables for multiple CSV files** and insert data efficiently, forming a **reliable and centralized data foundation** for vendor performance analysis.

🔗 [View Script](https://github.com/yourusername/vendor-ingestion-script)

### Example Output
```bash
Ingesting vendor_data.csv in db
Ingesting inventory_data.csv in db
--------------Ingestion Complete------------
Total Time Taken: 0.02 minutes
```
