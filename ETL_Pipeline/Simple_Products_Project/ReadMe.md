# Built a Simple ETL Project with Products data

**ETL Steps**

1. Extract
    - Read the data from the CSV file into a Python program.
    - Use libraries like pandas to load the CSV.

2. Transform
    - Clean and process the data.

    Examples:
   
       - Handle missing values (if any).   
       - Add calculated fields, like total stock value (price * stock_quantity).   
       - Normalize data, e.g., converting product names to lowercase.

4. Load
    - Store the transformed data into a PostgreSQL database.
    - Use libraries like SQLAlchemy or psycopg2 for database operations.
