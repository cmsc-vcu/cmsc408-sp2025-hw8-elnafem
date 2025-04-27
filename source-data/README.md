# CMSC 408 - Spring 2025 - Homework 8

## World Bank Indicator Analysis

---

This project explores and analyzes data from the World Bank's World Development Indicators (WDI) dataset using SQL and Python. The assignment focuses on querying, transforming, and analyzing global development data stored in a MySQL database.

### Project Structure

- `report.qmd`: Main Quarto report containing SQL queries, results, and analysis.
- `reports/helpers.py`: Helper functions to connect to the database, execute SQL, and handle results.
- `.env`: Stores database connection parameters (not included in repo for security reasons).

### Key Skills Practiced

- SQL `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`, `CASE`, and `JOIN` operations
- Advanced SQL: `CROSS JOIN`, pivot tables, subqueries, and percentage calculations
- Data cleaning: Identifying missing or anomalous entries
- Data aggregation and transformation
- Using Python with SQLAlchemy and Pandas to interact with databases
- Creating reproducible data analysis reports with Quarto

### Reflection

This assignment helped reinforce how relational databases can be used to answer complex questions about real-world datasets. It emphasized both basic querying skills and more advanced techniques like pivoting, cross joins, and percentage breakdowns. These are directly applicable to data analysis, backend development, and business intelligence work.

### Notes

- Before running the report, make sure your Python environment has the following libraries installed:
  - `pandas`
  - `sqlalchemy`
  - `python-dotenv`
  - `tabulate`
  - `pymysql`
  - `requests`
- Render the report with: 
  ```bash
  quarto render report.qmd
