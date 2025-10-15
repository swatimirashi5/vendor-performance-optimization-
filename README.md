# Vendor Performance Analysis Project

## Step 1 – Automated Data Ingestion

### Purpose
I built a Python script to automatically read **multiple vendor and inventory CSV files (5+ files, 10k+ rows each)** and load them into a **centralized SQLite database**.  
The script also logs which files were processed, how long it took, and any errors, ensuring the data is **reliable, organized, and ready for analysis**.  
This step creates a clean data foundation for the next stages of cleaning, transformation, and vendor performance evaluation.

### Tech Used
Python · Pandas · SQLAlchemy · SQLite · Logging  

### GitHub Script
[View Script](https://github.com/yourusername/vendor-ingestion-script)

### Example Output
```bash
Ingesting vendor_data.csv in db
Ingesting inventory_data.csv in db
--------------Ingestion Complete------------
Total Time Taken: 0.02 minutes
```

### Why This Step Matters
It converts messy raw CSV files into a **structured, centralized database**, making future analysis accurate, efficient, and scalable.

