# Dominican Republic Economic Data by JUN 2026 PROJECT

## Overview
This project aims to demostrate a full data workflow apply to economics: 

**Ingest macroeconomic data from bancentral.gov.do**
- GDP, GDP PPP and GDP Growth
- Inflation/monetary policy
- Foreign investment
- Human resorces
- Public dept

## Technologies
- Python (scraping, ETL, automation)
- SQL Server (data storage, schema design)
- Excel (data consumption)
- GitHub (version control)

## Structure
- `raw/` → raw scraped and downloaded files
- `clean/` → cleaned datasets
- `sql/` → SQL schema and scripts
- `scripts/` → Python pipeline scripts

## Workflow
1. Scrape → `raw/`
2. Clean → `clean/`
3. Load → SQL Server Tracking Data
4. Import → Excel Power Query
5. Visualize → Descriptive and Predictive Excel dashboards
6. Analytics → Written dignostics and prescriptive analysis

## Objectives
- Modular Python scripts for reproducibility
- SQL schema design for scrape tracking storage
- Logging and error handling in ELT
- Version control with Git and GitHub
- Future: scheduling jobs for automation
