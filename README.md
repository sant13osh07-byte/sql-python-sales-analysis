MySQL and Python Sales Analysis
Overview
This project explores sales transaction data stored in MySQL using Python and Jupyter Notebook. It demonstrates data retrieval, data-quality checks, basic cleaning, time-based analysis, and visual exploration of customer and sales performance.
Tools
- MySQL
- Python
- Jupyter Notebook
- mysql-connector-python
- Pandas and NumPy
- Matplotlib and Seaborn
Analysis included
- Retrieve transaction data from a MySQL table
- Inspect missing values and fill selected customer/product attributes using grouped values
- Explore customer age and customer attributes
- Extract date parts and summarize customer ratings by month
- Visualize order counts by day of week and hour
- Compare customer ratings with profit
- Explore payment methods and profit distributions
- Compare profit and order counts by product category
Repository contents
- mysql_python_sales_analysis.ipynb — analysis notebook
- README.md — project documentation
Requirements
Install Python, Jupyter, and the required libraries:
pip install jupyter pandas numpy matplotlib seaborn mysql-connector-python
Database setup
This notebook expects a MySQL database named sales containing a table named sales_transactions_2022_2025 with the columns referenced in the notebook.
Set the following environment variables before running, or enter the password when prompted:
- MYSQL_HOST (default: localhost)
- MYSQL_PORT (default: 3306)
- MYSQL_USER
- MYSQL_PASSWORD (optional; if not set, the notebook prompts for it)
- MYSQL_DATABASE (default: sales)
Do not upload database passwords, private credentials, or confidential customer data to GitHub.
Run
1. Start MySQL and ensure the database/table are available.
2. Install the required packages.
3. Open mysql_python_sales_analysis.ipynb in Jupyter Notebook.
4. Run the cells from top to bottom.
Notes
The original notebook relies on a locally available database and table. Results will only reproduce when the required schema and dataset are available. Add a permitted, anonymized sample dataset or a schema/setup script if you want others to reproduce the analysis.
Author
Data Analytics Portfolio Project
