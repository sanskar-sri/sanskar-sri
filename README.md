<div align="center">

# Sanskar Srivastava

### Geospatial Data Engineer · MLOps · Risk Analytics · Cloud Data Platforms

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sanskar--srivastava-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanskar-srivastava)
[![Email](https://img.shields.io/badge/Email-contact-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:Sanskar.2024GI06@mnnit.ac.in)
[![Open to work](https://img.shields.io/badge/Open_to_Work-Geospatial_DE_·_MLOps_·_Risk_Analytics_·_Data_Engineer-2ea44f?style=flat-square)](#)

</div>

---

I build **production-grade data platforms** at the intersection of geospatial AI, MLOps, and cloud data engineering.

My M.Tech thesis is a full geospatial MLOps platform — a cloud-portable Bronze/Silver/Gold data lake processing **119.78M+ mobile LiDAR points**, orchestrated with Airflow, tracked with MLflow, versioned with DVC, and delivering **92.82% segmentation accuracy** with downstream building inventory and risk exposure analytics.

Industry background: **Snowflake medallion warehouse + dbt Core** for Evoke plc · **BigQuery lakehouse** for OVO Energy (200K+ monthly survey responses, 60% query performance improvement).

**M.Tech Geoinformatics · MNNIT Prayagraj · GATE 2022 & 2024 · SPARC 2026 IIT Kanpur**

---

## What I bring to each company type

| | Company type | What they need | What I have |
|---|---|---|---|
| **Geospatial / LiDAR** | HERE · Esri · Hexagon · Bentley · Precisely | Point cloud ingestion, 3D segmentation, geospatial lake design, GIS export | Bronze/Silver/Gold LiDAR lake · PointNet++ / RandLA-Net / PTv3 · GeoJSON/GeoParquet · Rerun 3D visualisation · PostGIS · GeoPandas |
| **MLOps / Data Platform** | Databricks · Astronomer · dbt Labs · Weights & Biases | Pipeline orchestration, experiment tracking, dataset versioning, reproducible ML | Airflow DAG orchestration · MLflow model registry · DVC dataset versioning · Docker · GitHub Actions CI · compute health monitoring |
| **Risk Analytics** | Moody's · Swiss Re · Verisk · RMS · CoreLogic | Exposure data, building inventory, flood/cat risk scoring, governed pipelines | LiDAR-derived building inventory · flood depth exposure scoring · building height classification · detection confidence · GeoParquet risk outputs |
| **FAANG / Big Tech** | Google · Microsoft · Amazon · Adobe · Salesforce | Scalable pipelines, system design, data governance, cloud-native architecture | Snowflake + dbt Core + SCD 1/2/3 · BigQuery lakehouse · PySpark at scale · RBAC + PII masking · medallion architecture · 119M+ point pipeline |

---

## Featured project

### [LiDAR MLOps Platform](https://github.com/sanskar-sri/lidar-mlops-platform) — Geospatial · MLOps · Risk Analytics

<img width="1710" alt="LiDAR Platform — Rerun 3D semantic label viewer" src="https://github.com/user-attachments/assets/b6875c50-eaaa-47ab-ba91-c2765ec04977" />

End-to-end platform for mobile LiDAR building identification — from raw `.ply / .las / .laz` ingestion to a governed six-zone data lake on Backblaze B2 (S3-compatible), Airflow-orchestrated preprocessing on remote GPU workers, MLflow experiment tracking, DVC dataset versioning, 3D deep learning segmentation, and downstream risk/exposure analytics.

| Metric | Value |
|---|---|
| LiDAR points processed | 119.78M+ |
| Registered datasets | 5 |
| Segmentation accuracy | 92.82% (PTv3) |
| Models benchmarked | PointNet++ · PointNet++ MSG · RandLA-Net · PTv3 |
| Dashboard pages | 15 |
| Airflow DAGs | 4 |

**What it signals to each company type:**

- *Geospatial / LiDAR:* Cloud-portable LiDAR lake · 3D segmentation · Rerun visualisation · GeoJSON/GeoParquet export · building footprint extraction
- *MLOps:* Airflow DAG orchestration · MLflow + model registry · DVC versioning · Docker · GitHub Actions CI · compute health agents
- *Risk analytics:* Flood depth exposure scoring · building height classification · detection confidence · building inventory pipeline · S3-portable architecture
- *FAANG / Big Tech:* Medallion lake design · Parquet analytics layer · RBAC · PII masking · lazy service import pattern · key design decisions documented

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GeoParquet](https://img.shields.io/badge/GeoParquet-50ABF1?style=flat-square)
![Rerun](https://img.shields.io/badge/Rerun_SDK-5C4EE5?style=flat-square)

---

## Also building

### [snowflake-dbt-streaming-warehouse](https://github.com/sanskar-sri/snowflake-dbt-streaming-warehouse) — Data Engineering · Analytics Engineering

Snowflake medallion warehouse (RAW → STG → INT → MARTS) with Streams, Tasks, dbt Core, SCD Type 1/2/3, dimensional modeling, RBAC, and column-level PII masking. Based on production patterns from Evoke plc engagement.

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

---

### [bigquery-lakehouse](https://github.com/sanskar-sri/bigquery-lakehouse) — Data Engineering · GCP *(in progress)*

BigQuery Bronze → Silver lakehouse with partitioning, clustering, materialized views, dbt transformations, and automated data quality checks. Mirrors the OVO Energy analytics architecture pattern.

![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white)

---

## Full stack

**Data engineering & warehousing**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)

**MLOps & platform**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-00BEF0?style=flat-square)

**Geospatial & risk**

![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square)
![PostGIS](https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GeoParquet](https://img.shields.io/badge/GeoParquet-50ABF1?style=flat-square)
![Open3D](https://img.shields.io/badge/Open3D-black?style=flat-square)
![Rerun](https://img.shields.io/badge/Rerun_SDK-5C4EE5?style=flat-square)

**Cloud**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Backblaze B2](https://img.shields.io/badge/Backblaze_B2_(S3)-E02020?style=flat-square)

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
- **GATE 2024** — IISc Bangalore &nbsp;·&nbsp; **GATE 2022** — IIT Kharagpur

---

## Industry experience

| Role | Company | Client | Stack | Impact |
|---|---|---|---|---|
| Data Engineer Intern | Lognormal Analytics | Evoke plc (UK) | Snowflake · dbt Core · Snowpipe · Streams · Tasks | Medallion warehouse · near-real-time ELT · RBAC + PII masking |
| Software Engineer | HCLTech | OVO Energy (UK) | BigQuery · Looker Studio · GCP · PySpark | 60% query improvement · 200K+ monthly survey responses · 4 executive dashboards |

---

<div align="center">

**Open to:** `Geospatial Data Engineer` &nbsp;·&nbsp; `MLOps Engineer` &nbsp;·&nbsp; `Risk Analytics Engineer` &nbsp;·&nbsp; `Cloud Data Engineer` &nbsp;·&nbsp; `Analytics Engineer`

India — remote / hybrid / onsite

*M.Tech Geoinformatics · MNNIT Prayagraj · 2024–2026*

</div>
