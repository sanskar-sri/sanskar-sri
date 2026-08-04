<div align="center">

# Sanskar Srivastava

### Data Engineer · MLOps · Geospatial AI · Cloud Data Platforms

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sanskar--srivastava-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sanskar-srivastava-360666170)
[![Email](https://img.shields.io/badge/Email-sanskaranmol786@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sanskaranmol786@gmail.com)
[![Open to work](https://img.shields.io/badge/Open_to_Work-Data_Engineer_·_Analytics_Engineer_·_MLOps_·_Geospatial_DE-2ea44f?style=flat-square)](#)

</div>

---

I build **production-grade data platforms** — governed medallion architectures, orchestrated pipelines, and ML systems that are auditable end to end.

**Industry:** Snowflake medallion warehouse with dbt Core, Streams, and Tasks for **Evoke plc** · BigQuery lakehouse for **OVO Energy** — 200K+ monthly survey responses, 60% query performance improvement.

**Research:** My M.Tech thesis is a full geospatial MLOps platform that turns raw mobile LiDAR into a governed building inventory — **111.7M model-ready point entries** through a Bronze/Silver/Gold lake, Airflow-orchestrated on remote GPU workers, MLflow-tracked, DVC-versioned, delivering **0.9794 test mIoU** segmentation and per-building storey estimates published to BigQuery and Looker Studio.

**M.Tech Geoinformatics · MNNIT Prayagraj · GATE 2022 & 2024 · SPARC 2026, IIT Kanpur**

---

## What I bring, by role

| Role | What the role needs | What I've built |
|---|---|---|
| **Data / Analytics Engineer** | Warehouse modeling, ELT orchestration, data quality, governance | Snowflake medallion (RAW → STG → INT → MARTS) · dbt Core · SCD Type 1/2/3 · Streams + Tasks · RBAC + column-level PII masking · BigQuery partitioning & clustering |
| **MLOps / Platform Engineer** | Reproducibility, experiment tracking, orchestration, cost control | Airflow DAG orchestration to remote GPU workers · MLflow experiment tracking · DVC dataset versioning · Docker + GitHub Actions CI · readiness gates that fail before GPU spend · compute health agents |
| **Geospatial Data Engineer** | Point cloud ingestion, 3D ML, spatial data contracts, GIS delivery | Six-zone LiDAR lake on S3-compatible storage · PointNet++ SSG/MSG · RandLA-Net · DBSCAN + RANSAC instancing · GeoJSON / GeoPackage / GeoParquet export · Rerun 3D visualisation · GeoPandas · PostGIS |
| **Risk / Exposure Analytics** | Building inventory, exposure attributes, confidence-scored outputs | LiDAR-derived building inventory with footprint, height, storey count, confidence, and QA flags · flood depth exposure scoring · human-review routing for low-confidence records |

---

## Featured project

### [LiDAR MLOps Platform](https://github.com/sanskar-sri/Lidar-MLOps-Platform) — Data Engineering · MLOps · Geospatial AI

<img width="1710" alt="LiDAR Platform — Rerun 3D semantic label viewer" src="https://github.com/user-attachments/assets/b6875c50-eaaa-47ab-ba91-c2765ec04977" />

**The business problem:** municipalities, insurers, and telecom planners all need building height and floor-count data, and nobody has a reliable, current database of it. Physical survey doesn't scale. This platform drives the street once and produces governed table rows — with a confidence score and a flag for the records a human should check.

From raw `.ply / .las / .laz` ingestion → six-zone medallion lake on S3-compatible object storage → Airflow-orchestrated preprocessing on remote GPU workers → MLflow + DVC tracked training → DBSCAN and RANSAC building instancing → per-building storey estimation → BigQuery + Looker Studio review dashboard.

| Metric | Value |
|---|---|
| Model-ready point entries | **111.7M** across 6,818 Gold blocks |
| Best model | **PointNet++ SSG — 0.9794 test mIoU** |
| Building IoU / overall accuracy | 0.9695 / 0.9920 |
| Models benchmarked | PointNet++ SSG · PointNet++ MSG · RandLA-Net *(identical input contract and eval protocol)* |
| Held-out test set | 8.5M unique points, spatial split — no neighbourhood leakage |
| Final output | Per-building footprint, height, storey count, confidence, QA flags |
| Dashboard pages / Airflow DAGs | 15 / 4 |

**What it demonstrates:**

- **Data engineering** — medallion lake design, data contracts validated before training, Parquet analytics layer, checksums, lineage records keyed by `dataset_id / prep_version / model / run_id`
- **MLOps** — Airflow orchestration, MLflow tracking, DVC versioning, Docker, GitHub Actions CI, readiness gates that fail fast before expensive GPU runs
- **ML judgment** — the model with the *highest recall* was rejected: its lower precision produced 5.9× more false positives and fragmented downstream building instances. Upstream precision, not recall, controls output quality
- **Production thinking** — low-confidence and likely-merged instances are flagged for human review rather than published as clean records

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GeoParquet](https://img.shields.io/badge/GeoParquet-50ABF1?style=flat-square)
![Rerun](https://img.shields.io/badge/Rerun_SDK-5C4EE5?style=flat-square)

---

<img width="1710" height="1107" alt="Platform dashboard" src="https://github.com/user-attachments/assets/31fec7ac-cc1a-4169-8436-e6c80c3c2811" />

## Also building

### [retail-cdc-pipeline](https://github.com/sanskar-sri/retail-cdc-pipeline) — Streaming Data Engineering

Change data capture pipeline: PostgreSQL → Debezium → Kafka → BigQuery medallion architecture, with Bronze/Silver/Gold layers and an AI serving layer with SQL governance. Built to demonstrate CDC internals — log-based capture, schema evolution, and exactly-once semantics — end to end rather than as isolated components.

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-DD1100?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)

---

### [snowflake-dbt-streaming-warehouse](https://github.com/sanskar-sri/snowflake-dbt-streaming-warehouse) — Data Engineering · Analytics Engineering

Snowflake medallion warehouse (RAW → STG → INT → MARTS) with Streams, Tasks, dbt Core, SCD Type 1/2/3, dimensional modeling, RBAC, and column-level PII masking. Based on production patterns from the Evoke plc engagement.

![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

---

### [bigquery-lakehouse](https://github.com/sanskar-sri/bigquery-lakehouse) — Data Engineering · GCP *(in progress)*

BigQuery Bronze → Silver lakehouse with partitioning, clustering, materialized views, dbt transformations, and automated data quality checks. Mirrors the OVO Energy analytics architecture pattern.

![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![Looker](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white)

---

## Stack

**Warehousing & modeling**

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt_Core-FF694B?style=flat-square&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlebigquery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)

**Pipelines & orchestration**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-DD1100?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**MLOps & platform**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat-square&logo=mlflow&logoColor=white)
![DVC](https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Dash](https://img.shields.io/badge/Dash-00BEF0?style=flat-square)

**Geospatial**

![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square)
![PostGIS](https://img.shields.io/badge/PostGIS-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GeoParquet](https://img.shields.io/badge/GeoParquet-50ABF1?style=flat-square)
![Open3D](https://img.shields.io/badge/Open3D-black?style=flat-square)
![Rerun](https://img.shields.io/badge/Rerun_SDK-5C4EE5?style=flat-square)

**Cloud**

![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Backblaze B2](https://img.shields.io/badge/Backblaze_B2_(S3)-E02020?style=flat-square)

---

## Industry experience

| Role | Company | Client | Stack | Impact |
|---|---|---|---|---|
| Data Engineer Intern | Lognormal Analytics | Evoke plc (UK) | Snowflake · dbt Core · Snowpipe · Streams · Tasks | Medallion warehouse · near-real-time ELT · RBAC + PII masking |
| Software Engineer | HCLTech | OVO Energy (UK) | BigQuery · Looker Studio · GCP | 60% query performance improvement · 200K+ monthly survey responses · 4 executive dashboards |

---

## Recognition

- **SPARC 2026 International Conference, IIT Kanpur** — *Self-Supervised Learning for Near-Miss Pedestrian Risk Detection*
- **Certificate: Geospatial Technologies & Smart Cities** — IIT Kanpur
- **GATE 2024** — IISc Bangalore &nbsp;·&nbsp; **GATE 2022** — IIT Kharagpur

---

## GitHub activity

<div align="center">

![GitHub streak](https://streak-stats.demolab.com?user=sanskar-sri&theme=default&hide_border=true&date_format=j%20M%5B%20Y%5D)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=sanskar-sri&layout=compact&hide_border=true&theme=default&langs_count=6&cache_seconds=86400&v=2)

</div>

---

<div align="center">

**Open to:** `Data Engineer` &nbsp;·&nbsp; `Analytics Engineer` &nbsp;·&nbsp; `MLOps Engineer` &nbsp;·&nbsp; `Geospatial Data Engineer`

Bengaluru · Hyderabad · Pune · Remote — India

*M.Tech Geoinformatics · MNNIT Prayagraj · 2024–2026*

</div>
