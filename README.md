# IPL Data Engineering Pipeline  

## 📌 Project Overview  
This project focuses on building a **Data Engineering Pipeline** to process and analyze **IPL (Indian Premier League) match data** using **PySpark on Databricks**. The primary objective is to gain hands-on experience in the **end-to-end data lifecycle**—from **data extraction, preprocessing, transformation,** to **query-based analysis**.

The project begins by **loading the raw IPL dataset** into an **AWS S3 bucket**, making it a publicly accessible object to allow **Databricks** to read the data directly from S3. The dataset is then **ingested into Databricks**, where **PySpark** is used to perform **data cleansing** and **data quality checks** to identify inconsistencies or missing records.  

Once the raw data is **preprocessed**, various **business transformation logics** are applied to generate meaningful insights. The transformed data is **stored in temporary views**, and **SQL queries** are executed to generate **aggregated tables** for analysis.  

---

## **Architecture Diagram**  

![IPL Data Engineering Architecture](https://github.com/suryadeipreddyk/ipl-data-engineering-pipeline/blob/cf3987640a41b47aff45ec590df22b73930d38ee/IPL%20Data%20Engineering%20Architecture.png)  

---

For a detailed breakdown of the project, visit the [**Indian Premier League ETL Pipeline**](https://devengine.notion.site/Indian-Premier-League-ETL-Pipeline-1af32fa5808880108fe8c1562c7806f1?pvs=4).

---
