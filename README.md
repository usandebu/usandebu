## Hey, I'm Unai 👋

Data Engineer building lakehouse and streaming pipelines on Databricks, with GenAI/RAG layers on top of well-modelled data. I care about pipelines that are tested, observable and cheap to run: infrastructure as code, data quality checks and CI on every project.

Data Engineering · Lakehouse · Spark / PySpark · Streaming · Databricks · Delta Lake · dbt · Airflow · RAG on Databricks · Infrastructure as Code

## Featured projects

**[Energy Data Platform](https://github.com/usandebu/energy-data-platform)**: end-to-end lakehouse crossing Spanish electricity generation (REE) with daily weather (AEMET). Airflow orchestration, raw data in AWS S3 provisioned with Terraform, Bronze/Silver in Databricks + PySpark, Gold modelled and tested with dbt, per-run operational reports and a Databricks SQL dashboard. pytest, Ruff and GitHub Actions in CI.

**Public Procurement Intelligence** _(in progress)_: full-Databricks project over Spanish public tenders (PLACSP). Incremental ingestion of the official Atom feed into a Bronze/Silver/Gold lakehouse, tender documents parsed with `ai_parse_document`, indexed in Vector Search and served through a RAG app with citations (tender id + page), plus a Genie Space and dashboard over the Gold layer. The RAG is evaluated against a question set, not just demoed. Delivered with Asset Bundles and CI.

**[Realtime Transit Lakehouse](https://github.com/usandebu/realtime-transit-lakehouse)** _(in progress)_: streaming pipeline for live vehicle positions from Transport for London (JSON) and Berlin VBB (GTFS-Realtime / protobuf), normalized into a canonical schema, published to Kafka and processed with Spark Structured Streaming (watermarking, deduplication) into Delta Lake. Grafana for operations, Power BI for business. Phase 1 (TfL → Kafka → consumer) complete, with tests and CI.

## Tech stack

### Data Engineering & Cloud

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="32" alt="Python">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachespark/apachespark-original.svg" height="32" alt="PySpark">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="32" alt="Pandas">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="32" alt="NumPy">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" height="32" alt="Scikit-Learn">&nbsp;<img src="https://cdn.simpleicons.org/databricks/FF3621" height="32" alt="Databricks">&nbsp;<img src="https://cdn.simpleicons.org/delta/00ADD4" height="32" alt="Delta Lake">&nbsp;<img src="https://cdn.simpleicons.org/snowflake/29B5E8" height="32" alt="Snowflake">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachekafka/apachekafka-original.svg" height="32" alt="Kafka">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apacheairflow/apacheairflow-original.svg" height="32" alt="Airflow">&nbsp;<img src="https://cdn.jsdelivr.net/gh/gilbarbara/logos/logos/dbt-icon.svg" height="32" alt="dbt">&nbsp;<img src="https://cdn.jsdelivr.net/gh/gilbarbara/logos/logos/aws.svg" height="32" alt="AWS">&nbsp;<img src="https://cdn.jsdelivr.net/gh/gilbarbara/logos/logos/microsoft-azure.svg" height="32" alt="Azure">

> **Python:** PySpark · Pandas · NumPy · Scikit-Learn · Pytest
>
> **Databricks:** Delta Lake · Unity Catalog · Lakeflow Jobs · Auto Loader · Structured Streaming · Asset Bundles · Vector Search · Databricks SQL · Genie
>
> **Snowflake:** Warehouses · Snowpipe · Streams & Tasks
>
> **Streaming & Orchestration:** Kafka · Spark Structured Streaming · Airflow
>
> **Transformation:** dbt (models, tests, docs) · medallion architecture (Bronze/Silver/Gold) · incremental ingestion
>
> **AWS:** S3, EC2, IAM, Glue, Athena
>
> **Azure:** ADLS, Data Factory, Databricks, Synapse, Entra ID, SQL Database, Key Vault

### DevOps & Quality

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="32" alt="Docker">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" height="32" alt="Terraform">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="32" alt="Git">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" height="32" alt="GitHub Actions">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="32" alt="Bash">

> Docker · Terraform · GitHub Actions (CI/CD) · Git · Bash

### Databases & BI

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="32" alt="PostgreSQL">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="32" alt="MySQL">&nbsp;<img src="https://cdn.simpleicons.org/supabase/3FCF8E" height="32" alt="Supabase">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="32" alt="MongoDB">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/grafana/grafana-original.svg" height="32" alt="Grafana">&nbsp;<img src="https://cdn.jsdelivr.net/gh/gilbarbara/logos/logos/microsoft-power-bi.svg" height="32" alt="Power BI">

> PostgreSQL · MySQL · Supabase · MongoDB · SQL (window functions, CTEs, query optimization, execution plans, indexes)
>
> Grafana (operational monitoring) · Power BI (business reporting) · Databricks SQL Dashboards

### Backend & Web

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="32" alt="Java">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="32" alt="TypeScript">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="32" alt="JavaScript">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="32" alt="Node.js">&nbsp;<img src="https://cdn.simpleicons.org/express/888888" height="32" alt="Express">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nestjs/nestjs-original.svg" height="32" alt="NestJS">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="32" alt="FastAPI">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="32" alt="PHP">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-original.svg" height="32" alt="Laravel">&nbsp;<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="32" alt="React">&nbsp;<img src="https://cdn.simpleicons.org/nextdotjs/888888" height="32" alt="Next.js">

> Java · TypeScript · JavaScript · Node.js / Express · NestJS · FastAPI · PHP / Laravel · React · Next.js · RESTful APIs

## Find me

[LinkedIn](https://www.linkedin.com/in/unaisanchez26) | [Email](mailto:unai.sanchez.debustos@gmail.com) | [GitHub](https://github.com/usandebu)
