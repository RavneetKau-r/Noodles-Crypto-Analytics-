  Technical Runbook: Noodles Crypto Analytics

## System Overview-
The Noodles Crypto Analytics platform is an end to end data Analytics solution developed using python,MYSQL and Power Bi.
System Architecture
JSON Files-->Python ETL Pipeline-->MySQL Data Warehouse-->PowerBI Dashboards.
## Daily Operations
### Manual ETL Execution- 
**Activate Python Environment**: 
```bash source venv/bin/activate # or venv\Scripts\activate on Windows

source venv\Scripts\activate on Windows
Run Pipeline:
cd scripts
# Execute the notebook for data refresh


     Automated Execution (Cron/Task Scheduler)

Windows (Task Scheduler): Set up a task to run the script daily.
Open Task Scheduler
Create Basic Task: "Noodles ETL"
Trigger: Daily at 6:00 AM
Action: Start program
Program: C:\path\to\venv\Scripts\python.exe
Arguments: execute Task 6 notebook or equivalent refresh job
Start in: C:\path\to\noodles-analytics\scripts\

Power BI Refresh
Manual: Open Power BI Desktop and refresh.
Scheduled: Ensure it's set up in Power BI Service.
Monitoring & Validation
Check ETL Logs:
tail -n 50 logs/etl_$(date +%Y%m%d)*.log

Validate Data Quality: Run validation scripts in Jupyter.
Check  missing or Null Values
identify duplicate records
Validate Data types
Check primary and foreign key relationship

Troubleshooting
Common Issues: List potential errors and solutions, like missing modules or database connection issues.
File Locations
Paths:  key files and resources are located, e.g., data/raw/, logs/.
"C:\Users\bohar\Downloads\Noodles Crypto Analytics project"
Database Information
Details: Server: localhost
Database: NoodlesDW
Schemas: Staging, DW
Authentication: MySQL user from .env (e.g. root)

Key Contacts

Backup & Recovery
Database Backup: SQL commands for backup.
BACKUP DATABASE NoodlesDW TO DISK = 'C:\Backups\NoodlesDW_Full.bak'WITH FORMAT, INIT, NAME = 'Full Backup of NoodlesDW';

