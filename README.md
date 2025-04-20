# Task-7-Data-Analytics
### Connect to SQlite Database
Creates (or connects to) a SQLite database named sales_data.db.
conn is the connection object, and cursor allows you to execute SQL commands.
### Create a Table
Defines a table called sales with four columns: id (auto-incrementing primary key), product (text), quantity (integer), and price (real number for decimal values).
### Insert Sample Data
Inserts sample data into the sales table. executemany allows batch insertion. conn.commit() saves changes to the database.
### Query Data for Analysis
Performs a SQL query to calculate the total quantity (SUM(quantity)) and revenue (SUM(quantity * price)) for each product.
pd.read_sql_query converts the SQL result into a pandas DataFrame for easier manipulation.
# Display Result
Prints the sales summary (total quantities and revenue per product) to the console.
### Visualize Revenue with Matplotlib
Plots a bar chart with products on the x-axis and revenue on the y-axis.
### Close the Database connection
Closes the database connection to free up resources.
