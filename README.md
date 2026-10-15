## Hey, I'm Unai 👋

Data Engineer building lakehouse and streaming pipelines on Databricks, with GenAI/RAG layers on top of well-modelled data. I care about pipelines that are tested, observable and cheap to run: infrastructure as code, data quality checks and CI on every project.

Data Engineering · Lakehouse · Spark / PySpark · Streaming · Databricks · Delta Lake · dbt · Airflow · RAG on Databricks · Infrastructure as Code

## Featured projects

**[Energy Data Platform](https://github.com/usandebu/energy-data-platform)**: end-to-end lakehouse crossing Spanish electricity generation (REE) with daily weather (AEMET). Airflow orchestration, raw data in AWS S3 provisioned with Terraform, Bronze/Silver in Databricks + PySpark, Gold modelled and tested with dbt, per-run operational reports and a Databricks SQL dashboard. pytest, Ruff and GitHub Actions in CI.

**Public Procurement Intelligence** *(in progress)*: full-Databricks project over Spanish public tenders (PLACSP). Incremental ingestion of the official Atom feed into a Bronze/Silver/Gold lakehouse, tender documents parsed with `ai_parse_document`, indexed in Vector Search and served through a RAG app with citations (tender id + page), plus a Genie Space and dashboard over the Gold layer. The RAG is evaluated against a question set, not just demoed. Delivered with Asset Bundles and CI.

**[Realtime Transit Lakehouse](https://github.com/usandebu/realtime-transit-lakehouse)** *(in progress)*: streaming pipeline for live vehicle positions from Transport for London (JSON) and Berlin VBB (GTFS-Realtime / protobuf), normalized into a canonical schema, published to Kafka and processed with Spark Structured Streaming (watermarking, deduplication) into Delta Lake. Grafana for operations, Power BI for business. Phase 1 (TfL → Kafka → consumer) complete, with tests and CI.

## Tech stack

### Data, Cloud & Pipelines

<table><tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=py" width="48" height="48" alt="Python"><br><sub>Python</sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachespark/apachespark-original.svg" width="48" height="48" alt="PySpark"><br><sub>PySpark</sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="48" height="48" alt="Pandas"><br><sub>Pandas</sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="48" height="48" alt="NumPy"><br><sub>NumPy</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=sklearn" width="48" height="48" alt="Scikit-Learn"><br><sub>Scikit-Learn</sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/databricks/FF3621" width="48" height="48" alt="Databricks"><br><sub>Databricks</sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/delta/00ADD4" width="48" height="48" alt="Delta Lake"><br><sub>Delta Lake</sub></td>
<td align="center" width="96"><img src="https://cdn.simpleicons.org/snowflake/29B5E8" width="48" height="48" alt="Snowflake"><br><sub>Snowflake</sub></td>
</tr><tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=kafka" width="48" height="48" alt="Kafka"><br><sub>Kafka</sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apacheairflow/apacheairflow-original.svg" width="48" height="48" alt="Airflow"><br><sub>Airflow</sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/gilbarbara/logos/logos/dbt-icon.svg" width="48" height="48" alt="dbt"><br><sub>dbt</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=aws" width="48" height="48" alt="AWS"><br><sub>AWS</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=azure" width="48" height="48" alt="Azure"><br><sub>Azure</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=terraform" width="48" height="48" alt="Terraform"><br><sub>Terraform</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=docker" width="48" height="48" alt="Docker"><br><sub>Docker</sub></td>
</tr></table>

### Backend & Web

<table><tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=java" width="48" height="48" alt="Java"><br><sub>Java</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=ts" width="48" height="48" alt="TypeScript"><br><sub>TypeScript</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=js" width="48" height="48" alt="JavaScript"><br><sub>JavaScript</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=nodejs" width="48" height="48" alt="Node.js"><br><sub>Node.js</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=express" width="48" height="48" alt="Express"><br><sub>Express</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=nestjs" width="48" height="48" alt="NestJS"><br><sub>NestJS</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=fastapi" width="48" height="48" alt="FastAPI"><br><sub>FastAPI</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=php" width="48" height="48" alt="PHP"><br><sub>PHP</sub></td>
</tr><tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=laravel" width="48" height="48" alt="Laravel"><br><sub>Laravel</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=react" width="48" height="48" alt="React"><br><sub>React</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=nextjs" width="48" height="48" alt="Next.js"><br><sub>Next.js</sub></td>
</tr></table>

### Databases & Storage

<table><tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=postgres" width="48" height="48" alt="PostgreSQL"><br><sub>PostgreSQL</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=mysql" width="48" height="48" alt="MySQL"><br><sub>MySQL</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=supabase" width="48" height="48" alt="Supabase"><br><sub>Supabase</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=mongodb" width="48" height="48" alt="MongoDB"><br><sub>MongoDB</sub></td>
</tr></table>

### DevOps, Quality & BI

<table><tr>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=githubactions" width="48" height="48" alt="GitHub Actions"><br><sub>GitHub Actions</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=git" width="48" height="48" alt="Git"><br><sub>Git</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=github" width="48" height="48" alt="GitHub"><br><sub>GitHub</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=bash" width="48" height="48" alt="Bash"><br><sub>Bash</sub></td>
<td align="center" width="96"><img src="https://skillicons.dev/icons?i=grafana" width="48" height="48" alt="Grafana"><br><sub>Grafana</sub></td>
<td align="center" width="96"><img src="https://cdn.jsdelivr.net/gh/gilbarbara/logos/logos/microsoft-power-bi.svg" width="48" height="48" alt="Power BI"><br><sub>Power BI</sub></td>
</tr></table>

## Find me

[LinkedIn](https://www.linkedin.com/in/unaisanchez26) | [Email](mailto:unai.sanchez91@gmail.com) | [GitHub](https://github.com/usandebu)
