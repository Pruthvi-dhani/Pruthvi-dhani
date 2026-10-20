## Hi, I'm Pruthvi

Backend engineer with around 5 years building high-throughput transactional systems and the
large-scale data pipelines behind them, mostly in regulated finance. Currently a Software Engineer
at **JPMorganChase** in the UK.

I like owning a system end to end, from design through to living with it in production, whether
that means building it from nothing or making something that exists materially faster and cheaper
to run.

### What I've worked on

**JPMorganChase** · 2025 to present\
Distributed data platform behind firm-wide liquidity regulatory reporting. PySpark on AWS EMR
Serverless, with Java and Spring Boot services around it. Led the migration of 17 report pipelines
from cluster-based EMR to EMR Serverless, cut a core transformation stage from 40 to 10 minutes, and
led a four-person migration of 80 TB of history from on-prem Hadoop to Snowflake.

**Albaco** · 2023 to 2025\
One of the first backend engineers at a UK fintech. Built the Clearbank and Mambu payments
integration handling **500+ TPS**, deployed active-passive across two Azure regions; the backend for
a deposits origination platform; and a bitemporal SQL Server data warehouse orchestrated with
Airflow.

**Dhani** · 2021 to 2023\
Backend for a pan-India e-commerce app serving millions of users. Replaced a batch sync with a
Debezium and Kafka change-data-capture pipeline, taking sync latency from 15 minutes to under a
second, and used Redis distributed locking to cut peak MySQL load by 30%.

### Open source

| Project | What it is |
|---|---|
| [**reliable-messaging-spring-boot-starter**](https://github.com/Pruthvi-dhani/reliable-messaging-spring-boot-starter) | Drop-in Spring Boot starter for request idempotency and the transactional outbox. At-least-once delivery to Kafka with exactly-once effect, and a chaos test that kills the publisher mid-flight to prove no event loss. Java 21, Spring Boot 3.3, PostgreSQL, Kafka, Testcontainers. |
| [**sql-warden**](https://github.com/Pruthvi-dhani/sql-warden) | Governed SQL gateway for AI agents over MCP. Every query passes a server-side admission pipeline: allowlist validation, a cost gate using the engine's own planner, column masking, per-session budgets and a separate audit trail. PostgreSQL and Snowflake. Python 3.12, mypy strict. |

### Stack

- **Languages:** Java, Python, TypeScript, SQL
- **Backend:** Spring Boot, Spring Security, Hibernate, Django, FastAPI, Flask, React
- **Data:** Spark / PySpark, Snowflake, Airflow, Kafka, Debezium, PostgreSQL, SQL Server, MySQL, Redis, Elasticsearch
- **Cloud:** AWS (EMR, Lambda, Step Functions, DynamoDB, SQS), Azure (Functions, Container Apps, Cosmos DB), Docker, Kubernetes

### Background

MTech in Data Science and BTech in Civil Engineering, IIT Madras.

[LinkedIn](https://www.linkedin.com/in/pruthvij)
