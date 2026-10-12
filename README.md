# Awesome-Data-Pipeline-ETL

## Top Data Pipeline ETL Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Integration, Transformation & Pipeline Orchestration*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Pipeline & ETL**. These tools help organizations extract data from disparate sources, transform it for analytics, and load it into warehouses or lakes — enabling reliable data movement and transformation at scale.



**Examples** include Salesforce Data Pipelines, Fivetran, Airbyte Cloud, Stitch Data, Hevo Data, Matillion, portable.io, Estuary Flow, Meltano, and Rivery (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom connectors, and open pipeline orchestration — ideal for data engineers seeking transparent, vendor-independent data integration.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global data pipeline and ETL tools market is estimated at approximately **$12B–$15B in 2025** (scaling to **$35B–$48B by 2030** at ~20–26% CAGR), propelled by real-time streaming data, cloud warehouse adoption, and AI ingestion demands. The sector is **moderately to highly fragmented** rather than winner-take-all; while enterprise cloud giants and modern leaders hold strong footprints, the landscape supports diverse specialized solutions across managed ELT, stream processing, long-tail connectors, and thriving open-source ecosystems.



## SaaS/Hosted Platforms

| Platform | Description | Company Size / Valuation | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Data Pipelines](https://www.salesforce.com/)** | Salesforce-native data integration service connecting external data sources and Data Prep recipes to Data Cloud. | ~$290B+ Market Cap ($38B+ Rev) | $9,000/org/month (billed annually; requires Enterprise+) | No self-serve free tier/trial (Available via Salesforce Developer Edition org or custom Enterprise AE PoC) |
| **[Fivetran](https://www.fivetran.com/)** | Fully managed ELT platform with 700+ pre-built connectors and automated schema drift handling. | $5.6B Valuation (~$325M ARR) | $500/month (Starter tier; consumption based on MAR) | Free forever up to 500,000 MAR/month (or 14-day free trial with unlimited rows) |
| **[Airbyte Cloud](https://airbyte.com/)** | Cloud-managed version of open-source Airbyte with 600+ pre-built connectors. | $1.5B Valuation (~$18M–$20M ARR) | $15/month (Base Team tier; $2.50/credit consumption) | 30-day free trial with 400 free credits (valued at $2,000) |
| **[Matillion](https://www.matillion.com/)** | Cloud-native ELT platform with visual pipeline design and SQL pushdown transformation. | $1.5B Valuation (~$90M–$100M ARR) | $2.00–$2.50/credit (Task-hour consumption; ~$20,000/year minimum commit for Teams) | Developer Tier (Free forever for 1 developer user; plus 14-day trial with 500 free credits) |
| **[Rivery](https://rivery.io/)** | Cloud ELT platform with CDC capabilities, reverse ETL, and Python workflow support (acquired by Boomi). | ~$100M Acquired / $52M Raised (~$21M ARR) | $0.75–$0.90/credit (~$500/month for standard usage) | 14-day free trial with 1,000 free usage credits (no credit card required) |
| **[Stitch Data](https://www.stitchdata.com/)** | Cloud ELT built on the Singer framework with 130+ connectors (part of Qlik Talend). | $60M Acquired ($30M+ Raised) | $100/month (Standard plan for up to 5M rows/month) | 14-day free trial with unlimited row syncing and all plan features |
| **[Hevo Data](https://hevodata.com/)** | Automated no-code ELT platform with 150+ connectors and auto-healing data pipelines. | $43M Raised (~$45M ARR) | $265–$299/month (Starter plan; scales from 5M events/month) | Free forever plan with up to 1 Million events/month (limited to free connectors, 5 users) |
| **[Estuary Flow](https://estuary.dev/)** | Real-time batch and streaming data pipeline platform with low-latency CDC. | $24M Raised (Series A) | $0.50/GB + $100/month per active connector instance | Free forever plan up to 10 GB/month data transfer and 2 active connector instances |
| **[Meltano](https://meltano.com/)** | Managed cloud infrastructure and orchestration for open-source Singer pipelines (GitLab spin-off). | $12.4M Raised (Seed) | Starter tier with 200 compute hours/month (~$150–$300/mo estimated usage) | Meltano Open is Free forever (Cloud requires contacting sales / 14-day pilot upon request) |
| **[Portable.io](https://portable.io/)** | Managed ETL specializing in long-tail obscure SaaS APIs and custom bespoke connectors. | $3.24M Raised (Series A) | $1,800/month (Standard flat-rate unlimited volume plan) | 14-day free trial with unlimited connector testing and data syncing |



## Open-Source GitHub Projects



- **[Airbyte](https://github.com/airbytehq/airbyte)**  

  Leading open-source ELT platform (Elastic-2.0 for core) with 600+ pre-built connectors, 22k+ GitHub stars. Seamlessly sync data from any source to any destination. Most popular open-source alternative to Fivetran .



- **[Airtruct](https://github.com/sananguliyev/airtruct)**  

  Lightweight self-hosted alternative to Airbyte/Fivetran (Apache-2.0). Visual pipeline builder, built-in Bloblang transformations, coordinator/worker architecture for horizontal scaling, and MCP integration for AI assistants. Single binary, no Docker or JVM required .



- **[Apache NiFi](https://github.com/apache/nifi)**  

  Mature flow-based programming platform (Apache-2.0) for visual design and management of data pipelines. Web-based designer for routing, transforming, and mediating data. Fine-grained data provenance tracking from ingestion to delivery. Supports both batch and real-time .



- **[Apache Hop](https://github.com/apache/hop)**  

  Successor to Pentaho PDI (Apache-2.0). Metadata-driven architecture, visual pipeline builder, 400+ plugins. Runs on Spark, Flink, Google Dataflow, or AWS EMR through Apache Beam. Latest release 2.18 (June 2026) .



- **[dlt (data load tool)](https://github.com/dlt-hub/dlt)**  

  Python data ingestion framework (Apache-2.0). Schema inference engine automatically detects types and flattens nested JSON. AI-powered pipeline generation using LLMs to scaffold extraction code. Moves data to lakehouses, warehouses, or vector databases .



- **[Mage](https://github.com/mage-ai/mage-ai)**  

  Open-source data pipeline platform (Apache-2.0) for effortless integration, transformation, and orchestration using Python, SQL, and R. 8,800+ GitHub stars .



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  

  Open-source ELT platform (MPL-2.0) for cloud and security data. Infrastructure-as-code style pipelines. Extracts data from APIs/clouds to warehouse or lake with declarative configurations .



- **[Singer](https://github.com/singer-io)**  

  Open-source connector protocol (Apache-2.0) with vast ecosystem of taps (sources) and targets (destinations). Build exactly what you need with reusable components. Often paired with Meltano for orchestration .



- **[Artie](https://github.com/artie-labs/transfer)**  

  Open-source real-time CDC streaming (Apache-2.0). Streams database changes to data warehouses in ~10-20 seconds. Reduces warehouse costs by 50% by only transferring changed data .



- **[Kafka Connect + Debezium](https://github.com/debezium/debezium)**  

  Distributed CDC platform (Apache-2.0). Captures row-level changes from databases into Kafka topics. Robust CDC for low-latency streaming ETL. Requires Kafka operations expertise .



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Asset-based data orchestrator (Apache-2.0). Treats data assets as first-class primitives. Strong typing, validation, integrated testing, and built-in data observability. Code-as-configuration framework enabling software engineering practices .



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Most widely adopted workflow orchestration platform (Apache-2.0). Python-defined DAGs, massive operator ecosystem. Code-first approach with steep learning curve and operational complexity .



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Dynamic workflow orchestration (Apache-2.0). Declarative flows, hybrid cloud orchestration, REST API and CLI control. Easier setup than Airflow for on-demand execution .



- **[Apache SeaTunnel](https://github.com/apache/seatunnel)**  

  Distributed data integration engine (Apache-2.0). Supports structured and unstructured data sync across diverse sources/sinks. Multi-engine execution framework with visual pipeline designer and CDC tool .



- **[StreamSets Data Collector](https://github.com/streamsets/datacollector)**  

  Data pipeline platform (Apache-2.0 Community Edition). Data drift detection, built-in monitoring, GUI and API-driven development. Strong for hybrid batch-and-streaming environments .



### Additional Strong Open-Source Options



- **[Kestra](https://github.com/kestra-io/kestra)** — Declarative orchestration (Apache-2.0) unifying data, AI, and infrastructure workflows. YAML-based, language-agnostic .

- **[Apache Beam](https://github.com/apache/beam)** — Unified batch and streaming model (Apache-2.0) with pluggable runners (Flink, Spark, Dataflow) .

- **[Bruin](https://github.com/bruin-data/bruin)** — Multi-language data pipelines (SQL + Python) with built-in lineage .

- **[Logstash](https://github.com/elastic/logstash)** — Server-side data processing pipeline (Apache-2.0) for ingestion and transformation .

- **[Apache Camel](https://github.com/apache/camel)** — Enterprise integration framework with hundreds of connectors for routing and mediation .

- **[n8n](https://github.com/n8n-io/n8n)** — Workflow automation (Sustainable Use License) with 400+ connectors for lighter data integration .

- **[Marquez](https://github.com/MarquezProject/marquez)** — Open-source data lineage tracking (Java) .

- **[Elementary](https://github.com/elementary-data/elementary)** — dbt-native data observability (Apache-2.0) .



**Frameworks for building custom systems**: Combine **Airbyte** or **Airtruct** for connector-based ingestion with **Dagster** or **Kestra** for orchestration, **dbt** for in-warehouse transformation, **Debezium** for real-time CDC, and **Marquez** for data lineage — creating a fully self-hosted, enterprise-grade data pipeline platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data pipelines handling sensitive data must comply with data protection regulations (GDPR, CCPA, HIPAA, etc.).

- Self-hosted open-source solutions require proper security hardening, infrastructure provisioning, and ongoing maintenance. Total cost of ownership may exceed initial savings when accounting for developer time and infrastructure .



---



**Made for data engineers, analytics engineers, and developers building transparent data pipeline solutions.**  

Let's make Data Pipeline & ETL more open, data-driven, and efficient.
