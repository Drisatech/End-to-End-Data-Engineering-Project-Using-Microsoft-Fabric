# 🚀 End-to-End Data Engineering Pipeline Project Using Microsoft Fabric

This project demonstrates a complete end-to-end modern data engineering workflow built using Microsoft Fabric, leveraging key Fabric workloads such as Data Factory, OneLake, Synapse Data Engineering, Synapse Data Science, Power BI, and Data Activator.

The goal of this project is to build a unified data platform that supports:

✅ Automated data ingestion

✅ Data transformation & lake-house modeling

✅ Data science & machine learning

✅ Analytics & real-time reporting

✅ Action-based triggers & alerts


This project was implemented during a hands-on training in 2024, and showcases my ability to build enterprise-grade data pipelines using Microsoft Fabric.


---

🧠 Business Use Case

In this project, real-world data is ingested, processed, and transformed into insights for business users. The pipeline simulates how organizations collect data, enrich it, build predictive models, visualize performance trends in Power BI, and trigger automated business actions.


---

🏗️ Architecture Overview

Below is the architecture diagram used for this project:

> Architecture Source: Images/Project_Architecture.png





This architecture demonstrates how Microsoft Fabric unifies data engineering, storage, transformation, modeling, and business intelligence in one platform.


---

📦 Key Components

1️⃣ Data Ingestion – Microsoft Fabric Data Factory

Ingests raw data from external APIs / structured sources

Pipeline orchestrates ETL into OneLake

Supports triggered and scheduled workloads


2️⃣ OneLake (Delta Lake Storage)

Central unified lakehouse storage

Stores raw and curated data in Delta format

Shared storage across all Fabric services


> Lakehouse Screenshot: Images/LakeHouse_Model.png





---

3️⃣ Synapse Data Engineering

Used for notebook-based data transformation (PySpark)

Cleans, structures, and enriches the raw dataset

Loads data into Bronze → Silver → Gold tables



---

4️⃣ Synapse Data Science

Enables model training and experimentation

Data preparation for ML and feature engineering


> Example activities:



Exploratory Data Analysis (EDA)

Machine learning model integration

Scoring, predictions, and model outputs stored back in OneLake



---

5️⃣ Power BI – Analytics & Visualization

Interactive dashboards built on top of curated gold tables to provide real-time insights.

> Power BI Dashboard: Images/dashboard_1.png




Reports include:

Live interactive visuals

Performance metrics

Trend analysis



---

6️⃣ Data Activator – Real-Time Alerts

Watches metrics and thresholds in Power BI

Triggers automated business alerts / actions

Connects to Microsoft Teams for instant notifications


7️⃣ Microsoft Teams Integration

Receives automated alerts for anomaly detection

Enables business collaboration on insights



---

🔁 End-to-End Data Flow

Stage	Technology	Output

Data Source	API / Structured Source	Raw Data
Ingestion	Data Factory	Landing Zone
Storage	OneLake	Delta Tables
Transformation	Synapse Data Engineering	Curated Data
Analytics	Synapse Data Science + Power BI	Insights & ML Models
Automation	Data Activator	Alerts & Workflows
Collaboration	Teams	Real-time Notification



---

📂 Project Repo Structure

|-- Images/
|-- Python_Scripts/
|-- PowerBI/
|-- Meassure_Code_DAX.txt
|-- README.md


---

✅ Prerequisites

Microsoft Fabric Workspace access

OneLake enabled

Power BI Premium/Fabric capacity

Fabric workloads enabled:

Data Factory

Synapse Data Engineering

Synapse Data Science

Power BI

Data Activator


(Optional) External API subscription for ingestion



---

▶️ How to Run This Project

1. Clone repository


2. Open Microsoft Fabric workspace


3. Upload notebooks to Synapse Data Engineering


4. Configure Data Factory pipelines


5. Run ingestion workflow


6. Transform data in notebooks (Bronze → Silver → Gold)


7. Connect Power BI to OneLake


8. Publish dashboard & configure Data Activator triggers




---

📌 Deliverables

Component	Status

Lakehouse tables	✅
ETL Pipelines	✅
Data Engineering notebooks	✅
Power BI dashboard	✅
Real-time alert automation	✅
Architecture diagrams	✅



---

📝 License

This project is licensed under the MIT License.


---

👨‍💻 Author

Engr. Idris Aliyu
Assistant Technical Secretary, Nigerian Society of Engineers (NSE – Ajaokuta Branch)
Passionate about Data Engineering | Cloud | AI | Analytics


---

⭐ If you found this helpful, give the repo a star!

