# Noodles-Crypto-Analytics-
End -to-End Currency Analytics Platform using Python, MySQL   and Power Bi
# Noodles Crypto Analytics Platform

Dashboard screenshot: docs/screenshots/executive-dashboard.png

## Project Overview

Production-ready currency analytics platform processing 1M+ rows of
market data daily using Python, MySQL, and Power BI.

Key Features:
- Automated Python ETL pipeline (5-min runtime)
- Star schema data warehouse design
- Interactive Power BI dashboards
- Comprehensive data quality validation
- Scheduled daily refresh

## Architecture

json Files → Python ETL → MySQL (noodles_dw) → Power BI Dashboards

Architecture diagram (YOU CREATE in Task 9 §1):
docs/architecture-diagram.png

## Technology Stack

| Layer | Technology |
| ETL | Python 3.9, pandas, SQLAlchemy |
| Data Warehouse | MySQL 8.x |
| Visualization | Power BI Desktop, DAX |

## Project Structure

noodles-analytics/
├── 05_data_warehouse_design.ipynb
├── 06_powerbi_prep.ipynb
├── reports/          (Tasks 7–8 .pbix files)
├── docs/             ← YOU CREATE in Task 9
│   ├── architecture-diagram.png    ← §1
│   ├── data-dictionary.xlsx        ← §2
│   ├── technical-runbook.md        ← §3
│   ├── user-guide.md               ← §4
│   └── demo-presentation.pptx      ← §5
└── README.md

## Data Model

Dimensions: DimCurrency, DimDate, DimPlatform
Facts: FactSocialEngagement

Data dictionary 
docs/data-dictionary.xlsx

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

## Documentation  (files YOU CREATE — not pre-built reference links)

- Technical Runbook  →"C:\Users\bohar\Downloads\task 9\technical runbook.md"   
- User Guide         →          "C:\Users\bohar\Downloads\task 9\user guide.md"
- Architecture       →  "C:\Users\bohar\Downloads\task 9\architecture-diagram.png  
- Data Dictionary    → C:\Users\bohar\Downloads\task 9\Data Dictionary.xlsx       

## Demo

Demo video URL: "C:\Users\bohar\Downloads\task 9\demo-video.mp4.mp4"
Presentation:"C:\Users\bohar\Downloads\task 9\demo-presentation.pdf"
## Contact

Your Name Ravneet Kaur
ravn748@gmail.com
Optional — markdown link syntax for GitHub README only (after files exist in repo):

[Architecture Diagram]("C:\Users\bohar\Downloads\task 9\architecture-diagram.png")
[Data Dictionary]("C:\Users\bohar\Downloads\task 9\Data Dictionary.xlsx")
[Technical Runbook]("C:\Users\bohar\Downloads\task 9\technical runbook.md")
[User Guide]("C:\Users\bohar\Downloads\task 9\user-guide.md")
[Presentation slides]("C:\Users\bohar\Downloads\task 9\demo-presentation.pdf")
