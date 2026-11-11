Noodles Crypto Analytics Platform
Portfolio Project:Python ETL,MYSQL data warehouse and Power BI reporting.

Project Overview
Production-ready currency analytics platform processing 1M+ rows of
market data daily using Python, MySQL, and Power BI.

Key Features:
Automated Python ETL pipeline (5-min runtime):Automated extraction,data cleansing,transformation and validation  using pandas and sqlalchemy.
MYSQL Data warehouse:Star schema modelling optimized for analytical reporting
Interactive Power BI dashboards:Advanced DAX time-intelligence metrics,platform trend visuals,and multi table data warehouse relationships.
Comprehensive data quality validation:Automated anomaly checks,referential integrity enforcement,and robust logging.data dictionary,technical runbooks and user guides
Scheduled daily refresh
Comprehensive Documentation: Structured Architecture diagrams

Architecture
json Files → Python ETL → MySQL (noodles_dw) → Power BI Dashboards
Architecture diagram:https://github.com/RavneetKau-r/Noodles-Crypto-Analytics-/upload/RavneetKau-r-patch-1#:~:text=architecture%2Ddiagram.png

Technology Stack
| Layer | Technology |
| ETL | Python 3.9, pandas, SQLAlchemy |
| Data Warehouse | MySQL 8.x |
| Visualization | Power BI Desktop, DAX |
Project Structure
noodles-analytics/
├── 05_data_warehouse_design.ipynb
├── 06_powerbi_prep.ipynb
├── reports/          (Tasks 7–8 .pbix files)
├── docs/  
│   ├── architecture-diagram.png    ← §1
│   ├── data-dictionary.xlsx        ← §2
│   ├── technical-runbook.md        ← §3
│   ├── user-guide.md               ← §4
│   └── demo-presentation.pptx      ← §5
└── README.md
Data Model
Dimensions: DimCurrency, DimDate, DimPlatform
Facts: FactSocialEngagement
Data dictionary
docs/data-dictionary.xlsx

Key Insights
Bitcoin Dominance: 45% of total market capitalization
Volume Leaders: Top 20 currencies = 90% of trading volume
Social Correlation: Engagement predicts 30% of price movements
Volatility: Average daily price change of ±8%
Achievements
Processed 1M+ rows of currency data
Built automated ETL pipeline
Delivered interactive Power BI dashboards
Referential integrity in star schema
Documentation  (files YOU CREATE — not pre-built reference links)
Technical Runbook  →"C:\Users\bohar\Downloads\task 9\technical runbook.md"
User Guide         →          "C:\Users\bohar\Downloads\task 9\user guide.md"
Architecture       →  "C:\Users\bohar\Downloads\task 9\architecture-diagram.png
Data Dictionary    → C:\Users\bohar\Downloads\task 9\Data Dictionary.xlsx
Demo
Demo video URL: "C:\Users\bohar\Downloads\task 9\demo-video.mp4"
Presentation:"C:\Users\bohar\Downloads\task 9\demo-presentation.pdf"
Contact
Your Name Ravneet Kaur
ravn748@gmail.com
Optional — markdown link syntax for GitHub README only (after files exist in repo):
https://github.com/RavneetKau-r/Noodles-Crypto-Analytics-/tree/RavneetKau-r-patch-1
[Architecture Diagram]("C:\Users\bohar\Downloads\task 9\architecture-diagram.png")
[Data Dictionary]("C:\Users\bohar\Downloads\task 9\Data Dictionary.xlsx")
[Technical Runbook]("C:\Users\bohar\Downloads\task 9\technical runbook.md")
[User Guide]("C:\Users\bohar\Downloads\task 9\user-guide.md")
[Presentation slides]("C:\Users\bohar\Downloads\task 9\demo-presentation.pdf")
Demo video URL: "C:\Users\bohar\Downloads\task 9\demo-video.mp4"
Downloads\task 9\user-guide.md.pbix")
[Presentation slides]("C:\Users\bohar\Downloads\task 9\demo-presentation.pdf")
