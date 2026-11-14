# Noodles-Crypto-Analytics Platform
End -to-End Currency Analytics Platform using Python, MySQL   and Power Bi

Project:Noodles Crypto Analytics
Technologies:Python,MySQL and Power Bi,DAX

## Project Overview

Production-ready currency analytics platform processing 1M+ rows of
market data daily using Python, MySQL, and Power BI.
Executive Dashboard screenshot
https://1drv.ms/i/c/ca96d0cd9d062930/IQBMM6bMGerYRa3HGBOwAIfCAb7zeG4pw8hkbs1GDvbXvqU?e=wxngYg
https://1drv.ms/i/c/ca96d0cd9d062930/IQB9u58_fGNhQKIS2GQsQlkVAQF3fPWUigT0BX7Z2IA4yGI?e=Ps2235
("C:\Users\bohar\OneDrive\Documents\Noodle Analytics\task 8 docs\Screenshot (39).png")


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

- Technical Runbook  →https://github.com/RavneetKau-r/Noodles-Crypto-Analytics-/blob/f279cab0f69e20a7d22299514e738d685a4f1be1/Noodle%20Analytics/docs/technical%20runbook.md
- User Guide         →  https://github.com/RavneetKau-r/Noodles-Crypto-Analytics-/blob/82654843d42dbd3fffb2ad77011dba1ca5631ceb/Noodle%20Analytics/docs/user%20guide.md     
- Architecture diagram      →https://lucid.app/lucidchart/e21087d9-b503-432d-803b-fd4165062fbb/edit?viewport_loc=-96%2C-145%2C976%2C507%2C0_0&invitationId=inv_0e0541d1-568a-4cd0-9880-eecfb8c6f7da
- Data Dictionary    → https://1drv.ms/x/c/ca96d0cd9d062930/IQDTm3BcnPNUQonHhL5iUw1uAQFkYCY8DrJya322I4bjmZc?e=nDciYY
- demo Presentation -->https://1drv.ms/p/c/ca96d0cd9d062930/IQBhRofICB2ERIV-d3fUb7WLARCAu4qNoemgkndYCm5FCdI?e=QIUz6g
- final checklist--> https://github.com/RavneetKau-r/Noodles-Crypto-Analytics-/blob/7a87bda693ee4ed04ee1ba52446130d11f133b4a/Noodle%20Analytics/docs/final%20checklist.md  

## Demo

Demo video URL: https://youtu.be/9Vf6N2UH1UA


#Github repository
Repository:https://github.com/RavneetKau-r/Noodles-Crypto-Analytics-

## Contact

Name: Ravneet Kaur
ravn748@gmail.com 
