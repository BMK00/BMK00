<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=500&size=24&pause=1200&color=38BDF8&center=true&vCenter=true&width=560&lines=Data+Engineer;Airflow+%C2%B7+dbt+%C2%B7+PySpark+%C2%B7+Delta+Lake;Building+reliable%2C+scalable+data+pipelines" alt="Typing SVG" />

<p>
<a href="https://www.linkedin.com/in/mallikharjuna-karthik-balla-4a301042a"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=0A66C2" /></a>
<a href="mailto:karthik123bm@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=EA4335" /></a>
<a href="https://github.com/BMK00"><img src="https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=FFFFFF" /></a>
</p>

</div>

<br/>

## About

I design and build ELT/ETL pipelines that turn messy, multi-source data into analytics-ready tables — with an emphasis on data quality, incremental processing, and pipelines that don't break when upstream data does.

My work spans two patterns I care about most: **medallion architecture** (Bronze → Silver → Gold on Databricks and Delta Lake) and **incremental, CDC-style pipelines** (watermark extraction, dbt merge strategies, SCD2 snapshots) orchestrated with Airflow.

<br/>

## Tech Stack

<p>
<img src="https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=3776AB" />
<img src="https://img.shields.io/badge/SQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1" />
<img src="https://img.shields.io/badge/Apache_Airflow-0D1117?style=flat-square&logo=apacheairflow&logoColor=017CEE" />
<img src="https://img.shields.io/badge/dbt-0D1117?style=flat-square&logo=dbt&logoColor=FF694B" />
<img src="https://img.shields.io/badge/PySpark-0D1117?style=flat-square&logo=apachespark&logoColor=E25A1C" />
<img src="https://img.shields.io/badge/Databricks-0D1117?style=flat-square&logo=databricks&logoColor=FF3621" />
<img src="https://img.shields.io/badge/Delta_Lake-0D1117?style=flat-square&logo=delta&logoColor=00ADD8" />
<img src="https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=4169E1" />
<img src="https://img.shields.io/badge/AWS-0D1117?style=flat-square&logo=amazonaws&logoColor=FF9900" />
<img src="https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=2496ED" />
<img src="https://img.shields.io/badge/Git-0D1117?style=flat-square&logo=git&logoColor=F05032" />
<img src="https://img.shields.io/badge/Linux-0D1117?style=flat-square&logo=linux&logoColor=FCC624" />
</p>

<br/>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[airflow-dbt-postgres-cdc-finance](https://github.com/BMK00/airflow-dbt-postgres-cdc-finance)**

Incremental, CDC-style finance transactions pipeline. Airflow reads a watermark to pull only changed rows, dbt merges them into an incremental fact table, and a snapshot tracks account history with full SCD2 auditability.

`Airflow` `dbt` `PostgreSQL` `Incremental Models` `SCD2`

</td>
<td width="50%" valign="top">

**[fmcg-databricks-data-pipeline](https://github.com/BMK00/fmcg-databricks-data-pipeline)**

End-to-end medallion pipeline (Bronze → Silver → Gold) merging two companies' sales data into one unified analytics layer, with Delta Lake CDF, Unity Catalog, and Lakeflow Jobs feeding a BI dashboard.

`PySpark` `Delta Lake` `Unity Catalog` `Lakeflow Jobs`

</td>
</tr>
</table>

<br/>

## Currently

- Building out incremental and CDC-style patterns with Airflow + dbt across different warehouses
- Deepening Delta Lake internals — Change Data Feed, time travel, and Unity Catalog governance
- Always happy to talk through pipeline design, medallion architecture, or data quality tradeoffs

<br/>

<div align="center">

*Open to data engineering roles — reach out on [LinkedIn](https://www.linkedin.com/in/mallikharjuna-karthik-balla-4a301042a) or by [email](mailto:karthik123bm@gmail.com).*

</div>
