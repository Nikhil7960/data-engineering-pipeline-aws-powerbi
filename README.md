# 🚀 End-to-End Data Engineering Pipeline with AWS & Power BI

## 📌 Project Overview
This project demonstrates a complete **end-to-end data engineering pipeline** built using AWS services and visualized through Power BI.

The goal of this project is to transform raw support logs and ticket data into **structured, analytics-ready data** and generate meaningful insights for decision-making.

---

## 🏗️ Architecture
The pipeline follows a modern data engineering architecture:

- 📥 Data Source: Support Logs & Ticket Data  
- ☁️ Storage: Amazon S3 (Raw & Processed Data)  
- ⚙️ Processing:
  - AWS Lambda (Log Processing)
  - AWS Glue (ETL for ticket data)
- 🧠 Query Layer: Amazon Athena  
- 🏢 Data Warehouse: Amazon Redshift  
- 📊 Visualization: Power BI  

---

## 🔄 Data Pipeline Flow

1. Raw data is ingested into **Amazon S3**
2. AWS Lambda processes log data
3. AWS Glue performs ETL transformations
4. Processed data is stored back in S3
5. Amazon Athena is used for querying data
6. Cleaned data is loaded into Amazon Redshift
7. Power BI connects to Redshift for visualization

---

## 🧹 Data Cleaning & Transformation
- Removed duplicate records  
- Handled missing values  
- Fixed inconsistent log levels (e.g., INF0 → INFO, DEBG → DEBUG)  
- Removed invalid/negative response time values  
- Standardized categorical data  

---

## 📊 Key Insights
- ~83% tickets successfully resolved  
- 100% resolution rate for Phone & Email channels  
- Average response time ~983 ms  
- Stable system performance (CPU usage ~53%)  
- Feature request tickets take the highest resolution time  

---

## 🛠️ Tech Stack

- **Cloud**: AWS (S3, Lambda, Glue, Athena, Redshift)  
- **Programming**: Python (Pandas, NumPy)  
- **Data Processing**: ETL Pipelines  
- **Visualization**: Power BI  

---

## 💡 Learnings
- Built a complete ETL pipeline using AWS services  
- Learned how to handle real-world messy datasets  
- Understood data warehousing and querying  
- Created interactive dashboards for business insights  

---

## 🚀 Future Improvements
- Automate pipeline using Apache Airflow  
- Add real-time streaming (Kafka/Kinesis)  
- Improve dashboard with advanced KPIs  

---

## 🔗 Connect with Me
If you found this project interesting, feel free to connect with me on LinkedIn!

---
