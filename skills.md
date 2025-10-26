---
layout: single
title: Skills
classes: wide
sidebar:
title: "Skills"
toc: true
toc_label: "On this page"
toc_sticky: true
author_profile: true
---

Please view my [LinkedIn page](https://www.linkedin.com/in/jonathanlgreenwood/details/certifications/) for a list of my up-to-date qualifications. 

Please note this page is regulary updated.



# Languages
## SQL

| Concept | Description | Examples from my Portfolio |
|---|---|---|
| **Filtering and conditions** | `WHERE`, `IN`, `BETWEEN`, `LIKE` — selecting relevant data cleanly |[02_L1/helper_L1_sales_columns.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/02_L1/helper_L1_sales_columns.sql)|
| **Joins** | Inner, left, right, and self joins for combining multiple tables |[05_Enrichment/l2_macros.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/05_Enrichment/l2_macros.sql)|
| **Aggregations** | `GROUP BY`, `SUM`, `AVG`, `COUNT`, and conditional aggregation via `CASE WHEN` |[05_Enrichment/KPIs/kpi_month_var.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/05_Enrichment/KPIs/kpi_month_var.sql)|
| **Subqueries and CTEs** | Modular transformations and stepwise query logic |[05_Enrichment/KPIs/kpi_seasonality_strength.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/05_Enrichment/KPIs/kpi_seasonality_strength.sql)|
| **Window functions** | `ROW_NUMBER()`, `LAG()`, `LEAD()`, running totals, and partitioned averages |[02_L1/02_L1_keys.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/02_L1/02_L1_keys.sql)|
| **Data reshaping** | Pivoting, unpivoting, and flattening hierarchical data |[04_L2/02_create_L2_sales_long.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/04_L2/02_create_L2_sales_long.sql)|
| **Data cleaning and validation** | Handling nulls, deduplication, and constraint awareness (`NOT NULL`, `UNIQUE`) |[02_L1/01_L1_from_L0_ingest_std.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/02_L1/01_L1_from_L0_ingest_std.sql)|
| **Schema literacy** | Understanding fact/dimension models, keys, and relationships |[05_Enrichment/l2_macros.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/05_Enrichment/l2_macros.sql)|
| **Performance awareness** | Knowing what indexes do, and writing efficient queries (avoiding cross joins, subquery loops) |[02_L1/02_L1_keys.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/02_L1/02_L1_keys.sql)|
| **Transactions (light)** | Basic `BEGIN / COMMIT / ROLLBACK` understanding for safe updates or staging |[]()|
| **Analytical reporting** | Building datasets for dashboards — KPIs, time comparisons, YoY, MAPE, bias |[05_Enrichment/KPIs/kpi_product_coeff.sql](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/05_Enrichment/KPIs/kpi_product_coeff.sql)|
| **Data warehousing concepts** | OLAP vs OLTP awareness; star and snowflake schema fundamentals |[]()|
| **ETL logic in SQL** | Using SQL to transform raw → standardized → analytical tables (L0–L2 pipeline pattern) |[Process Overview](/projects/business-insights/index.html#Process%20Overview)|

## Python

| Library / Concept | Description / Use Case | Evidence |
|---|---|---|
| **pandas** | Data manipulation and cleaning (eg filtering, joins, aggregations, reshaping) | [034_profile_parquets.py](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/06_L2_to_pbi/034_profile_parquets.py)|
| **pyarrow** | Efficient data interchange and Parquet file handling | [033_split_parquet.py](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/06_L2_to_pbi/033_split_parquet.py)|
| **duckdb** | SQL querying within Python; fast analytics on Parquet files | [01_create_L0_db.py](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/01_Setup_Database/01_create_L0_db.py)|
| **os / pathlib** | File and folder management for automated ETL scripts | []()|
| **Jupyter / VS Code notebooks** | Interactive analysis, documentation, and rapid prototyping | [schema_columns.ipynb](https://github.com/jonnylgreenwood/Business-Insights/blob/main/Python/schema_columns.ipynb)|
| **Data visualization** | Quick checks using `matplotlib` / `plotly` | []()|
| **Basic Python syntax** | Loops, conditionals, list comprehensions, functions | [034_profile_parquets.py](https://github.com/jonnylgreenwood/Business-Insights/blob/main/SQL/06_L2_to_pbi/034_profile_parquets.py)|
| **Environment setup** | Using virtual environments, requirements.txt management | [requirements.txt](https://github.com/jonnylgreenwood/Business-Insights/blob/main/requirements.txt)|
| **Error handling & logging** | Try/except, basic logging for pipeline reliability | []()|


## DAX

[Business Insights](https://github.com/jonnylgreenwood/Business-Insights/blob/main/Power%20Bi/dax/measures.dax)

Variables, time intelligence, x and other functions.

## Power Query M formula language

[Business Insights](https://github.com/jonnylgreenwood/Business-Insights/blob/main/Power%20Bi/m_code/read_parquets.m)

Custom M code tweaking when appropiate.

# Software / Platforms

Use the links below to see examples of my work.

## Power BI
[Live Demo - Business Insights](/portfolio-site/projects/business-insights/insights.html)

Views based on the type of data and audience. See Live Demo for more detail.

## Alteryx

Example coming soon: data cleansing, transformation, apps and macros.

## Power Query
See [Power Query M formula language](#power-query-m-formula-language)

## GitHub
[jonnylgreenwood](https://github.com/jonnylgreenwood/)

All project code, documentation, and version history are hosted on GitHub.

## Excel
[Pricing File Example](/portfolio-site/assets/pricing_example.pdf)

Example of analytical modelling and structured price calculation in Excel. Information redacted - example of front end sheet for Sales Team. There were nine pages tailored to each lot, so a backend calculation page collated the infomation and calculations were done in one, more managable sheet.

## Visual Studio Code
[![Example of workspace](/portfolio-site/assets/images/vscode.png)](/portfolio-site/assets/images/vscode.png)

Shows how I manage workspaces, virtual environments, dependencies, and version control.

<!-- https://chatgpt.com/s/t_68fe36988c3c81918768f8d72314b7e4 -->