<div align="center">

# Sanskar Srivastava

**Data Engineer · MLOps · Geospatial AI & Risk Analytics**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/sanskar-srivastava)
[![Email](https://img.shields.io/badge/Email-Sanskar.2024GI06@mnnit.ac.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:Sanskar.2024GI06@mnnit.ac.in)
[![Open to work](https://img.shields.io/badge/Open_to_Work-Geospatial_DE_·_MLOps_·_Risk_Analytics_·_Data_Engineering-2ea44f?style=flat-square)](https://linkedin.com/in/sanskar-srivastava)

</div>

---

I build **production-grade data platforms** at the intersection of geospatial AI, MLOps, and cloud data engineering — processing 119M+ LiDAR points, orchestrating Airflow pipelines, and turning raw point clouds into governed, model-ready datasets with downstream risk and exposure analytics.

**M.Tech Geoinformatics · MNNIT Prayagraj · SPARC 2026 IIT Kanpur · GATE 2022 & 2024**

---

## What I bring to each domain

<table>
<tr>
<th>Company type</th>
<th>What they need</th>
<th>What I have</th>
</tr>
<tr>
<td><b>Geospatial / LiDAR</b><br><sub>HERE · Esri · Hexagon · Bentley · Precisely</sub></td>
<td>Point cloud ingestion, 3D segmentation, geospatial lake design, GIS export</td>
<td>Bronze/Silver/Gold LiDAR lake · PointNet++ · RandLA-Net · PTv3 · GeoJSON/GeoParquet export · Rerun 3D visualisation · PostGIS · GeoPandas</td>
</tr>
<tr>
<td><b>MLOps / Data Platform</b><br><sub>Databricks · Astronomer · dbt Labs · Weights & Biases</sub></td>
<td>Pipeline orchestration, experiment tracking, dataset versioning, reproducible ML workflows</td>
<td>Airflow DAGs · MLflow model registry · DVC dataset versioning · Docker deployment · compute health monitoring · medallion architecture</td>
</tr>
<tr>
<td><b>Risk Analytics</b><br><sub>Moody's · Swiss Re · Verisk · RMS · CoreLogic · BlackRock</sub></td>
<td>Exposure data management, building inventory, flood/catastrophe risk scoring, governed data pipelines</td>
<td>LiDAR-derived building inventory · flood depth exposure scoring · building height classification · detection confidence · GIS export for risk overlays · S3-portable exposure lake</td>
</tr>
<tr>
<td><b>FAANG / Big Tech</b><br><sub>Google · Microsoft · Amazon · Adobe · Salesforce</sub></td>
<td>Scalable pipelines, clean system design, governed data at scale, cloud-native architecture</td>
<td>Snowflake + dbt Core + SCD 1/2/3 · BigQuery lakehouse · PySpark at scale · Parquet analytics layer · RBAC + PII masking · 119M+ point pipeline</td>
</tr>
</table>

---

## Projects

### [Cloud-Portable Geospatial Data Lake & MLOps Platform](https://github.com/sanskar-sri/data-platform)

> Geospatial · MLOps · Risk Analytics

End-to-end platform for mobile LiDAR building identification — from raw `.ply / .las / .laz` ingestion to a governed Bronze → Silver → Gold lake on Backblaze B2, Airflow-orchestrated preprocessing, MLflow experiment tracking, DVC dataset versioning, and 3D deep learning segmentation with downstream risk and exposure analytics.

**Scale:** 119.78M+ LiDAR points · 5 registered datasets · 92.82% segmentation accuracy

**What it demonstrates for each company type:**

- *Geospatial / LiDAR:* Cloud-portable LiDAR lake · PointNet++ / RandLA-Net / PTv3 · Rerun 3D viewer · GeoJSON/GeoParquet export · building footprint extraction
- *MLOps:* Airflow DAG orchestration · MLflow tracking + model registry · DVC versioning · Docker deployment · compute health agents · reproducible run payloads
- *Risk analytics:* Flood depth exposure scoring · building height classification · detection confidence · building inventory pipeline · S3-portable lake architecture
- *Big tech:* Medallion architecture · Parquet analytics · RBAC · PII masking · lazy service import pattern · service-based Dash control plane

**Stack:**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet/GeoParquet-50ABF1?style=flat-square)
![PostGIS](https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

### [Snowflake dbt ELT Pipeline](https://github.com/sanskar-sri/snowflake-dbt-pipeline) *(in progress)*

> Data Engineering · Analytics Engineering · FAANG · Risk Analytics

Production-pattern Snowflake medallion warehouse (RAW → STG → INT → MARTS) with dbt Core — incremental models, SCD Type 1/2/3, schema tests, sources, Snowpipe ingestion, Streams + Tasks for CDC, RBAC, and column-level PII masking.

**Signals:** Snowflake · dbt Core · Dimensional Modeling · SCD · Governance · Data Quality

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

### [BigQuery Analytics Lakehouse](https://github.com/sanskar-sri/bigquery-lakehouse) *(in progress)*

> Data Engineering · GCP · FAANG · Risk Analytics

BigQuery Bronze → Silver lakehouse with partitioning, clustering, and materialized views; dbt transformations; automated data quality checks; and Looker Studio dashboard templates — mirroring enterprise CX and risk analytics architecture patterns.

**Signals:** BigQuery · GCP · dbt · Looker · Lakehouse Architecture · Data Quality

![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white)

---

## Full stack

**Data engineering**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Spark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)

**MLOps**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Geospatial & risk**

![PostGIS](https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square)
![GeoParquet](https://img.shields.io/badge/GeoParquet-50ABF1?style=flat-square)
![Open3D](https://img.shields.io/badge/Open3D-black?style=flat-square)
![Rerun](https://img.shields.io/badge/Rerun_SDK-5C4EE5?style=flat-square)

**Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![B2](https://img.shields.io/badge/Backblaze_B2_(S3)-E02020?style=flat-square)

---

## GitHub stats

<div align="center">

![GitHub stats](https://github-readme-stats.vercel.app/api?username=sanskar-sri&show_icons=true&theme=default&hide_border=true&count_private=true&include_all_commits=true)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sanskar-sri&layout=compact&hide_border=true&theme=default&langs_count=6)

</div>

---

## Recognition

- **SPARC 2026 International Conference, IIT Kanpur** — *Self-Supervised Learning for Near-Miss Pedestrian Risk Detection*
- **Certificate: Geospatial Technologies & Smart Cities** — IIT Kanpur
- **GATE 2024** — IISc Bangalore &nbsp;|&nbsp; **GATE 2022** — IIT Kharagpur

---

<div align="center">
<sub>M.Tech Geoinformatics · MNNIT Prayagraj · 2024–2026 · Open to roles across India (remote / hybrid / onsite)</sub>
</div>
