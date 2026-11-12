<h1>Kumar Vaibhav Sharma</h1>

**Cloud Data Platform Engineer** · McKinney, Texas

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaibhav-sharma-6b5184174)
[![Email](https://img.shields.io/badge/Email-kumar.sharma7862%40gmail.com-555?style=flat&logo=gmail&logoColor=white)](mailto:kumar.sharma7862@gmail.com)
[![DZone](https://img.shields.io/badge/DZone-Article-2E8B57?style=flat)](https://dzone.com/articles/modernization-is-not-migration)

I build and secure large-scale data platforms on Google Cloud. 10+ years in
regulated financial services: migrations, governed CI/CD and infrastructure
as code. Currently a Cloud Data Platform Engineer at **Ford Credit**.

---

## Highlights at Ford Credit

| | |
|---|---|
| 💰 **$552K a year saved** | Led a Teradata → BigQuery migration and improved performance by 12% |
| ⏱️ **7–8 h → under 3 h** | Rebuilt a 500-job DataStage nightly run on OpenShift with Jenkins |
| 🔐 **Governed CI/CD** | Change-ticket checks, per-environment approvers, commit provenance on production deploys |
| 🏗️ **GCP in Terraform** | VPC, load balancing, firewalls, DNS, IAM, KMS encryption |

---

## Pro bono work

### 🏊 Swim Across America: donation & registration analytics
*Data platform volunteer · 2026–present*

Built the nonprofit's analytics pipeline from scratch on Google Cloud. It
replaced a manual CSV-export and Tableau Prep process with an automated warehouse.

```
Convio SOAP API ──► staging ──► MERGE ──► BigQuery star schema ──► BI views
                                  │
                                  └──► load audit · change log
Cloud Scheduler ──► Cloud Run (hourly, ~40 s per run) ──► alerts on failure
```

- **Incremental loads** with per-source watermarks. Edited records are
  corrected in place and logged.
- **Composite keys** where source IDs collide
- **Audit reconciliation** validated across ~**943,000 donation records**
- **Alerts** if a run fails or stops running

---

## Talks & writing

- 🎤 **DevOpsCon New York 2026**: *Governed by Design: How Embedded CI/CD
  Controls Cut Release Time by 55% in a Regulated Data Platform*
- ✍️ **DZone**: [Modernization Is Not Migration](https://dzone.com/articles/modernization-is-not-migration)

---

## Tools

**Cloud** · GCP (BigQuery, Dataproc, Dataflow, Cloud Run) · AWS · Azure · Kubernetes · OpenShift<br>
**Data** · Spark / PySpark · Kafka · Airflow · dbt · Dataform · Informatica · DataStage<br>
**Platform** · Terraform · Docker · GitHub Actions · Cloud Build · Jenkins · Tekton<br>
**Languages** · Python · SQL · Scala · Shell
