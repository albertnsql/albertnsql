# Albert Nadar
**Senior Analytics Engineer (Business Intelligence & Product Analytics)** · Snowflake · dbt · Looker · SQL · Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-albertn97-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/albertn97)

---

## About

I'm a Senior BI / Analytics Engineer with 6+ years of experience building
analytics infrastructure that Finance, Product, and Marketing teams actually
trust and use.

My focus is the layer between raw data and business decisions governed
semantic layers, clean dbt models, and dashboards (and increasingly,
AI interfaces) that answer the question before someone has to ask it.

---

## Stack

| Layer | Tools |
|---|---|
| Data Warehouse | Snowflake |
| Transformation | dbt Core |
| Semantic Layer | dbt MetricFlow, Looker (LookML) |
| BI / Visualization | Looker, Tableau, SSRS |
| Languages | SQL, Python |
| Backend / AI | FastAPI, RAG (ChromaDB), LLM orchestration |
| Cloud | AWS |
| Other Databases | SQL Server, Oracle |

---

## Highlights

- Built **SemanticGateway**  a governed semantic layer that translates natural
  language into validated Snowflake SQL via MetricFlow, with zero hallucinated
  joins or grain violations
- Modeled **Customer LTV analytics** across 1M+ customers — driving retention
  and segmentation decisions for Finance and Marketing
- Built **50+ executive and financial dashboards** spanning revenue, margin,
  forecasting, and product performance
- Improved **forecasting accuracy by 35%** through analytical modeling and
  cleaner upstream data contracts
- Led **self-service analytics adoption** via semantic modeling, LookML
  governance, and stakeholder training

---

## Featured Projects

### [SemanticGateway](https://github.com/albertnsql/semantic-gateway)
Live app: https://semanticgateway.vercel.app

A governed semantic layer that turns natural language into validated Snowflake
SQL — without hallucinated joins, metric misuse, or grain violations. The LLM
handles intent extraction and narrative generation only; all SQL is generated
by MetricFlow from a governed semantic manifest, then reviewed for grain
mismatches and fan-out risk before it ever touches Snowflake. Built on a
synthetic streaming-SaaS dataset (1.8M+ rows, 18 certified metrics, 30 dbt
models, 79/79 tests passing), with RAG-based metric retrieval, a three-tier
LLM fallback chain, and a two-layer cache bringing warm queries down to
~1–3 seconds. Ships with an offline eval harness for scoring intent-extraction
accuracy against a pinned golden set.

`FastAPI` `MetricFlow` `dbt` `Snowflake` `RAG` `React` `OpenRouter`

### [LookML Auditor](https://github.com/albertnsql/lookml-auditor-web)
Live app: https://lookml-auditor-web.vercel.app

LookML Auditor is a powerful, privacy-first static analysis tool for Looker projects.
It helps developers maintain high quality code by detecting broken references, duplicate definitions,
and join integrity issues all in one beautiful dashboard.

`Python` `looker` `parser` `lookml` `react`

### [SaaS Product Analytics](https://github.com/albertnsql/saas-product-analytics)
Analytics pipeline for a synthetic SaaS dataset — synthetic event data
generated with Python, modeled in dbt, and structured to answer product and
growth questions like activation rates, feature adoption, and churn signals.

`Python` `dbt` `Product Analytics` `Churn` `Activation`

### [Instacart Analytics Engineering](https://github.com/albertnsql/instacart-analytics-dbt-looker)
End-to-end analytics engineering project on the Instacart dataset.
Built on Snowflake + dbt + LookML with a full star schema, customer RFM
segmentation, cohort retention analysis, and a semantic layer with reusable
explores and metrics.

`Snowflake` `dbt` `LookML` `Star Schema` `RFM` `Cohort Analysis`

---

## Currently Exploring

- **Agentic analytics interfaces** — extending SemanticGateway's pattern
  (governed semantic layer + LLM orchestration) to more complex, multi-step
  analytical workflows
- **Python for analytics engineering** — data profiling, pipeline scripting,
  and pandas for pre-modeling EDA
- **Fraud & fintech data modeling** — signal design and behavioral feature
  engineering for risk and AML use cases

---

## Certifications
- Google Business Intelligence Certificate
- Microsoft Certified: Azure Database Administrator Associate

---

## Connect
[linkedin.com/in/albertn97](https://www.linkedin.com/in/albertn97)
