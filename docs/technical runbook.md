Technical Runbook

Noodles Crypto Analytics Platform

1. System Overview

The Noodles Crypto Analytics Platform is an end-to-end data pipeline developed using Python, MySQL and Power BI.

The system processes source data through an ETL pipeline and stores the transformed information in a structured Data Warehouse.

2. Technology Stack

Component| Technology
Programming| Python
Data Processing| Pandas
Database| MySQL
Database Management| MySQL Workbench
Development| JupyterLab
Visualisation| Power BI
Automation| Windows Task Scheduler

3. Project Structure

The project contains the following main components:

- "notebooks/" – Jupyter notebooks for data processing.
- "reports/" – Generated reports and outputs.
- "docs/" – Technical documentation.
- "data/" – Project datasets.
- "scripts/" – Python ETL scripts, if applicable.

4. Environment Setup

Open Command Prompt and navigate to the project directory:

cd C:\Users\bohar\Dowmloads\noodles-analytics

Create a virtual environment:

python -m venv venv

Activate the environment:

venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

5. ETL Execution

The ETL process includes three main stages:

Stage 1: Extract

- Read source datasets.
- Load data into Python.
- Validate source data.

Stage 2: Transform

- Clean missing values.
- Remove duplicate records where appropriate.
- Convert data types.
- Apply business transformation rules.

Stage 3: Load

- Connect to MySQL.
- Load processed data into staging tables.
- Transform and load data into the Data Warehouse.

6. Database Management

Open MySQL Workbench and connect to the MySQL Server.

Select the project database:

USE noodles_dw;

Check available tables:

SHOW TABLES;

Check records:

SELECT * FROM your_table_name LIMIT 10;

7. Data Validation

Perform basic validation after ETL execution.

SELECT COUNT(*)
FROM your_table_name;

Check for duplicate records using the appropriate business key.

Verify that the expected staging and warehouse tables contain records.

8. Power BI Connection

1. Open Power BI Desktop.
2. Select Get Data.
3. Choose the MySQL database connector or configured ODBC connection.
4. Enter the MySQL server and database details.
5. Authenticate.
6. Select the required warehouse tables.
7. Load the data.
8. Refresh the report.

9. Database Backup

Create a backup directory:

mkdir C:\Backups

Run the following command in Windows Command Prompt:

mysqldump -u root -p --databases noodles_dw > C:\Backups\noodles_dw_backup.sql

Enter your MySQL password when prompted.

10. Database Recovery

To restore the backup, run:

mysql -u root -p < C:\Backups\noodles_dw_backup.sql

Verify the restored database and tables in MySQL Workbench.

11. Automation

Windows Task Scheduler can be configured to execute the ETL script automatically.

Configuration:

- Open Task Scheduler.
- Select Create Task.
- Configure the required schedule.
- Set the Python executable as the program.
- Provide the ETL script as the argument.
- Configure the project directory as the working directory.
- Save and test the task.

12. Troubleshooting

Error| Possible Solution
Python environment error| Activate the virtual environment.
MySQL connection failed| Check MySQL Server and connection credentials.
Missing Python package| Install dependencies from requirements.txt.
ETL execution failed| Review Python error messages and logs.
Power BI connection failed| Verify MySQL connection settings and drivers.
Missing warehouse records| Review ETL loading and transformation steps.

13. Maintenance

Recommended maintenance activities:

- Monitor ETL execution.
- Validate database records.
- Maintain regular database backups.
- Check Power BI refresh status.
- Review error logs.
- Update Python dependencies when required.

14. Conclusion

The Noodles Crypto Analytics Platform provides an integrated solution for data processing, warehousing and business intelligence reporting using Python, MySQL and Power BI.
  
  
  
BACKUP DATABASE NoodlesDW TO DISK = 'C:\Backups\NoodlesDW_Full.bak'WITH FORMAT, INIT, NAME = 'Full Backup of NoodlesDW';

