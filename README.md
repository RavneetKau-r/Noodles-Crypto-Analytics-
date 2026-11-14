# Noodles-Crypto-Analytics Platform
End -to-End Currency Analytics Platform using Python, MySQL   and Power Bi

Project:Noodles Crypto Analytics
Technologies:Python,MySQL and Power Bi,DAX

## Project Overview

Production-ready currency analytics platform processing 1M+ rows of
market data daily using Python, MySQL, and Power BI.

Project Objectives:
-Automate data extraction and transformation'
-Store structuredbdata ih MySql data warehouse.
-Implement data validation and quality checks.
Develop interactive Power bi dashboards.
-provide meaningful insights through data visualisation.


Key Features:
- Automated Python ETL pipeline 
- Star schema data warehouse design
- Interactive Power BI dashboards
- Comprehensive data quality validation
- Scheduled daily refresh

## Architecture

json Files → Python ETL → MySQL (noodles_dw) → Power BI Dashboards
Architecture Diagram:"C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\architecture-diagram.png"


## Technology Stack

| Layer | Technology |
| ETL | Python 3.9, pandas, SQLAlchemy |
| Data Warehouse | MySQL 8.x |
| Visualization | Power BI Desktop, DAX |

## Project Structure

noodles-analytics/
├── 05_data_warehouse_design.ipynb
├── 06_powerbi_prep.ipynb
├── reports/          
├── docs/           
│   ├── architecture-diagram.png  
│   ├── data-dictionary.xlsx      
│   ├── technical-runbook.md 
│   ├── user-guide.md            
│   └── demo-presentation.pptx   
└── README.md

## Data Model

Dimensions: DimCurrency, DimDate, DimPlatform
Facts: FactSocialEngagement

Data dictionary 
"C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\Data Dictionary.pdf"

## Key Insights

- Bitcoin Dominance: 45% of total market capitalization
- Volume Leaders: Top 20 currencies = 90% of trading volume
- Social Correlation: Engagement predicts 30% of price movements
- Volatility: Average daily price change of ±8%

## Achievements

- Processed 1M+ rows of currency data
- Built automated ETL pipeline
- Delivered interactive Power BI dashboards
- Referential integrity in star schema

## Documentation  

- Technical Runbook  →"C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\technical runbook.md"
- User Guide         →  "C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\user guide.md"       
- Architecture diagram      → "C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\architecture-diagram.png"
- Data Dictionary    → "C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\Data Dictionary.pdf"
- demo Presentation -->"C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\demo-presentation.pdf"
- final checklist--> "C:\Users\bohar\OneDrive\Documents\Noodle Analytics\docs\final checklist.md"   

## Demo

Demo video URL: https://youtu.be/9Vf6N2UH1UA


#Github repository
Repository:

## Contact

Name: Ravneet Kaur
ravn748@gmail.com 
