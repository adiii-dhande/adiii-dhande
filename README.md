<!-- Repo: adiii-dhande/adiii-dhande  →  README.md -->

<div align="center">

<img src="banner.svg" width="100%" alt="Aditya Dhande - Data Engineer | Data & AI | AWS Data Engineer | Analytics Engineer | Data Analyst" />

<br/>

![Profile Views](https://hits.sh/github.com/adiii-dhande.svg?style=for-the-badge&label=Profile%20Views&color=00b4d8)
![Followers](https://img.shields.io/github/followers/adiii-dhande?label=Followers&style=for-the-badge&logo=github&color=7B2FF7)
![Location](https://img.shields.io/badge/Nagpur%2C%20India-FF5722?style=for-the-badge&logo=googlemaps&logoColor=white)
![Open To Work](https://img.shields.io/badge/Open%20to%20Work-00C853?style=for-the-badge&logo=handshake&logoColor=white)

</div>

---

## 🧬 `whoami`

```python
class AdityaDhande:
    role       = "Data Engineer | Data & AI"
    education  = "B.Tech, Electronics & Telecommunication (YCCE Nagpur)"
    data_eng   = ["ELT/ETL Pipelines", "dbt", "Snowflake", "Spark", "Airflow", "Kafka"]
    ai         = ["Generative AI", "LLMs", "RAG", "Agentic AI"]
    cloud      = ["AWS (S3, IAM, Glue, Lambda, Redshift, EMR, EC2)", "Azure"]
    pipeline   = "Source → S3 → Snowflake → dbt (Bronze/Silver/Gold) → BI / AI apps"
    open_to    = "Mumbai · Pune · Hyderabad · Bangalore · Remote 🇮🇳"
    mindset    = "Reliable data pipelines are the foundation of every great AI system."
```

- ⚙️ Build **ELT pipelines** with **dbt + Snowflake + Spark** using **medallion (Bronze/Silver/Gold)** architecture
- 🧱 Strong in **data modeling**: Star Schema, SCD Type 2, facts & dimensions, incremental loads
- ✅ Data quality first: validated **200K+ records** with SQL & Python, automated checks and dbt tests
- 🤖 Bridging **Data → AI**: **Generative AI, LLMs, RAG & Agentic AI** powered by clean, governed data
- ☁️ Cloud: **AWS** (S3, IAM, Glue, Lambda, Redshift, EMR, EC2) and **Azure**
- 📊 BI-ready: **Power BI + DAX** dashboards on top of the gold layer

---

## 🔄 Data & AI Architecture

```mermaid
flowchart LR
    A[("📥 Sources<br/>CSV · DB · APIs")] --> B["☁️ AWS S3<br/>Raw Landing"]
    B --> C["❄️ Snowflake<br/>Storage Integration<br/>External Stage"]
    C --> D["🥉 Bronze"]
    D --> E["🥈 Silver"]
    E --> F["🥇 Gold"]
    F --> G["📊 Power BI<br/>Dashboards"]
    F --> I["🤖 RAG / LLM<br/>Agentic AI Apps"]
    H["🛠️ dbt<br/>Models · Tests · Snapshots"] -.-> D
    H -.-> E
    H -.-> F
    style A fill:#0072FF,color:#fff,stroke:#00F5FF
    style B fill:#FF9900,color:#000,stroke:#fff
    style C fill:#29B5E8,color:#000,stroke:#fff
    style D fill:#CD7F32,color:#fff
    style E fill:#C0C0C0,color:#000
    style F fill:#FFD700,color:#000
    style G fill:#F2C811,color:#000,stroke:#fff
    style H fill:#FF694B,color:#fff
    style I fill:#8E44AD,color:#fff,stroke:#fff
```

---

## 🛠️ Tech Stack

### 🏗️ Data Engineering
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white)
![ETL/ELT](https://img.shields.io/badge/ETL%20%2F%20ELT-00C853?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Medallion](https://img.shields.io/badge/Medallion%20Architecture-FFB300?style=for-the-badge&logo=databricks&logoColor=black)
![Star Schema](https://img.shields.io/badge/Star%20Schema%20%7C%20SCD%20Type%202-8E24AA?style=for-the-badge&logo=diagramsdotnet&logoColor=white)

### 🤖 Data & AI
![Generative AI](https://img.shields.io/badge/Generative%20AI-8E44AD?style=for-the-badge&logo=openai&logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs-FF4F8B?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0A66C2?style=for-the-badge&logo=databricks&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-00C2A8?style=for-the-badge&logo=robotframework&logoColor=white)

### ☁️ Cloud
![S3](https://img.shields.io/badge/AWS%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Glue](https://img.shields.io/badge/AWS%20Glue-8C4FFF?style=for-the-badge&logo=amazonaws&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![Redshift](https://img.shields.io/badge/AWS%20Redshift-8C4FFF?style=for-the-badge&logo=amazonredshift&logoColor=white)
![EMR](https://img.shields.io/badge/AWS%20EMR-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![IAM](https://img.shields.io/badge/AWS%20IAM-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Data Factory](https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

### 🧮 Languages & Databases
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-B41717?style=for-the-badge&logo=jinja&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### 📈 BI & Analytics
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C9BB8?style=for-the-badge&logo=python&logoColor=white)

### 🧰 Dev Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">

### ❄️ Airbnb Data Engineering Pipeline (AWS + Snowflake + dbt)
End-to-end **cloud ELT pipeline**: 5.7K+ Airbnb records (bookings, listings, hosts) from **AWS S3 → Snowflake**, transformed through **Bronze / Silver / Gold** with **11 dbt models**.

- ☁️ Secure S3 → Snowflake ingestion using **AWS IAM**, **Storage Integration** & **External Stages**
- ⚡ Incremental models with unique keys, so only new/changed rows load
- 🕰️ **3 dbt snapshots (SCD Type 2)** for history tracking
- 🧩 **4 reusable Jinja macros** + config-driven joins
- ✅ dbt tests (not-null, unique, business rules) between layers
- ⭐ Fact & dimension tables + one-big-table model for analytics

![AWS S3](https://img.shields.io/badge/AWS%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![AWS IAM](https://img.shields.io/badge/AWS%20IAM-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Jinja](https://img.shields.io/badge/Jinja-B41717?style=flat-square&logo=jinja&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

[![View Repo](https://img.shields.io/badge/View%20Repo-00F5FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/adiii-dhande/Airbnb-Snowflake-dbt-Pipeline)

</td>
    <td width="50%" valign="top">

### 🛒 E-Commerce Customer & Sales Analytics
Full analytics workflow: **Pandas cleaning**, **MySQL analysis** and an **interactive Power BI dashboard** with DAX KPIs, on 128 fictional transaction lines (Jan to Oct 2025).

- 🧹 Cleaned missing values, duplicates, cancelled & inconsistent records
- 🔎 Revenue trends, top products, repeat-purchase behavior
- 🌍 Country-level sales insights with a country tile slicer
- 📊 DAX KPIs: net revenue, orders, customers, AOV, plus month-over-month trend badges
- 📝 Documented KPI definitions, assumptions, findings and recommendations

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

[![View Repo](https://img.shields.io/badge/View%20Repo-00F5FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/adiii-dhande/E-Commerce-Customer-Sales-Analytics)

</td>
  </tr>
  <tr>
    <td colspan="2" valign="top">

### 🤖 Agentic AI Data Pipeline Assistant &nbsp; ![Status](https://img.shields.io/badge/Status-In%20Progress-FFB300?style=flat-square)
AI-powered data engineering assistant that uses an LLM agent to automate data ingestion, cleaning, validation, SQL generation and pipeline troubleshooting through natural-language instructions.

- 🧠 Natural-language to pipeline / SQL generation
- 📂 Automated dataset ingestion & schema profiling
- 🧹 AI-assisted cleaning & data-quality detection
- 🔍 Automated validation & pipeline error analysis
- ⚡ SQL generation and query optimization
- 🔄 Agent workflow: plan → execute → validate → report

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-FF4F8B?style=flat-square&logo=openai&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic%20AI-00C2A8?style=flat-square&logo=robotframework&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

[![View Repo](https://img.shields.io/badge/View%20Repo-00F5FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/adiii-dhande/Agentic-AI-Data-Pipeline-Assistant)

</td>
  </tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=adiii-dhande&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=adiii-dhande&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<br/>

<img src="https://streak-stats.demolab.com/?user=adiii-dhande&theme=tokyonight&hide_border=true" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=adiii-dhande&theme=tokyo-night&hide_border=true&area=true&custom_title=Contribution%20Graph" width="100%" />

</div>

---

## 🏆 Certifications

![McKinsey](https://img.shields.io/badge/McKinsey.org-Forward%20Program%20(Core%20Skills)-0B3D91?style=for-the-badge)
![Google](https://img.shields.io/badge/Google-Advanced%20Data%20Analytics-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Deloitte](https://img.shields.io/badge/Deloitte-Data%20Analytics%20Simulation-86BC25?style=for-the-badge&logo=deloitte&logoColor=white)
![Python](https://img.shields.io/badge/Python%20for%20Everybody-Coursera-0056D2?style=for-the-badge&logo=coursera&logoColor=white)

---

## 📫 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aditya-dhande-17a851255/)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://adittyyad.lovable.app/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adityadhande35@gmail.com)

<br/>

```sql
SELECT 'Let''s build scalable data pipelines for AI' AS message;
```

</div>
